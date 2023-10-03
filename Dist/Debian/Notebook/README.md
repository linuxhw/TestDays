Debian - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Debian.

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

Total: 7982

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Laptop 14s-fq1xxx           | [3709e611a3](https://linux-hardware.org/?probe=3709e611a3) | Oct 01, 2023 |
| Acer          | AOA150                      | [969a729098](https://linux-hardware.org/?probe=969a729098) | Oct 01, 2023 |
| Apple         | MacBook4,1                  | [d17d6d2b70](https://linux-hardware.org/?probe=d17d6d2b70) | Oct 01, 2023 |
| HP            | Pavilion Laptop 15t-eg30... | [ed7bf5aee1](https://linux-hardware.org/?probe=ed7bf5aee1) | Oct 01, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [83d91ea2fe](https://linux-hardware.org/?probe=83d91ea2fe) | Sep 30, 2023 |
| Juana Mans... | SF20GM7                     | [b2b359c659](https://linux-hardware.org/?probe=b2b359c659) | Sep 30, 2023 |
| Juana Mans... | SF20GM7                     | [ccb9b4e795](https://linux-hardware.org/?probe=ccb9b4e795) | Sep 30, 2023 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [e7dad368d2](https://linux-hardware.org/?probe=e7dad368d2) | Sep 30, 2023 |
| Dell          | Latitude 5410               | [8234abf02b](https://linux-hardware.org/?probe=8234abf02b) | Sep 30, 2023 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [de3079ae33](https://linux-hardware.org/?probe=de3079ae33) | Sep 30, 2023 |
| IX1401        | Unknown                     | [c77c1d010e](https://linux-hardware.org/?probe=c77c1d010e) | Sep 30, 2023 |
| HP            | Pavilion dv5                | [0b1da8643f](https://linux-hardware.org/?probe=0b1da8643f) | Sep 30, 2023 |
| Alienware     | m15 R4                      | [a67899ed06](https://linux-hardware.org/?probe=a67899ed06) | Sep 30, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | [703170e428](https://linux-hardware.org/?probe=703170e428) | Sep 30, 2023 |
| HP            | Notebook                    | [193ec8deb3](https://linux-hardware.org/?probe=193ec8deb3) | Sep 30, 2023 |
| HP            | ProBook 450 G1              | [1cbae5b56a](https://linux-hardware.org/?probe=1cbae5b56a) | Sep 29, 2023 |
| HP            | Pavilion dv9000 (GA359UA... | [cea70d5f75](https://linux-hardware.org/?probe=cea70d5f75) | Sep 29, 2023 |
| Dell          | Latitude 5410               | [61ddf0adf6](https://linux-hardware.org/?probe=61ddf0adf6) | Sep 29, 2023 |
| Dell          | Inspiron 5570               | [0e12b69b96](https://linux-hardware.org/?probe=0e12b69b96) | Sep 29, 2023 |
| Lenovo        | ThinkPad T500 22439AG       | [e5a2cd9816](https://linux-hardware.org/?probe=e5a2cd9816) | Sep 29, 2023 |
| Lenovo        | ThinkPad E490 20N8000SRT    | [274b3b5210](https://linux-hardware.org/?probe=274b3b5210) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [c61d70bcfa](https://linux-hardware.org/?probe=c61d70bcfa) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 16ABR8 82... | [1fcc841148](https://linux-hardware.org/?probe=1fcc841148) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [be49c167d0](https://linux-hardware.org/?probe=be49c167d0) | Sep 28, 2023 |
| Apple         | MacBookAir7,2               | [c25eeffab1](https://linux-hardware.org/?probe=c25eeffab1) | Sep 28, 2023 |
| Acer          | Acadia V1.35                | [c2074b2535](https://linux-hardware.org/?probe=c2074b2535) | Sep 28, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [3cb2bdba37](https://linux-hardware.org/?probe=3cb2bdba37) | Sep 27, 2023 |
| EUROCOM       | RACER 2.0                   | [4351733d37](https://linux-hardware.org/?probe=4351733d37) | Sep 27, 2023 |
| HP            | ElitePad 1000 G2            | [2668770971](https://linux-hardware.org/?probe=2668770971) | Sep 27, 2023 |
| Fujitsu       | LIFEBOOK E4512              | [08b39b38bd](https://linux-hardware.org/?probe=08b39b38bd) | Sep 27, 2023 |
| ASUSTek       | K50IJ                       | [8556633dad](https://linux-hardware.org/?probe=8556633dad) | Sep 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [1317c1f1a9](https://linux-hardware.org/?probe=1317c1f1a9) | Sep 27, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [1a472d3072](https://linux-hardware.org/?probe=1a472d3072) | Sep 27, 2023 |
| Dell          | Latitude E6530              | [40cdcd2545](https://linux-hardware.org/?probe=40cdcd2545) | Sep 27, 2023 |
| Acer          | Aspire 5951G                | [cae145acab](https://linux-hardware.org/?probe=cae145acab) | Sep 26, 2023 |
| Dell          | Vostro 14-3468              | [3fceb34932](https://linux-hardware.org/?probe=3fceb34932) | Sep 26, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [d406193722](https://linux-hardware.org/?probe=d406193722) | Sep 26, 2023 |
| Dell          | Vostro 14-3468              | [a027aae826](https://linux-hardware.org/?probe=a027aae826) | Sep 26, 2023 |
| Dell          | XPS 9315                    | [6fa1beb451](https://linux-hardware.org/?probe=6fa1beb451) | Sep 26, 2023 |
| Lenovo        | ThinkPad T420 4236EV9       | [d621ecd81f](https://linux-hardware.org/?probe=d621ecd81f) | Sep 26, 2023 |
| Lenovo        | ThinkPad L540 20AUS00N00    | [a8aee3f386](https://linux-hardware.org/?probe=a8aee3f386) | Sep 26, 2023 |
| Aquarius      | NS585                       | [ce1c1d6e56](https://linux-hardware.org/?probe=ce1c1d6e56) | Sep 26, 2023 |
| Acer          | Aspire A515-47              | [3c1e418bf0](https://linux-hardware.org/?probe=3c1e418bf0) | Sep 26, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [9e9ff26362](https://linux-hardware.org/?probe=9e9ff26362) | Sep 26, 2023 |
| Acer          | Aspire A515-56              | [b047457fd1](https://linux-hardware.org/?probe=b047457fd1) | Sep 25, 2023 |
| Dell          | XPS 15 9560                 | [a524453c71](https://linux-hardware.org/?probe=a524453c71) | Sep 25, 2023 |
| Lenovo        | G710 20252                  | [d7926809d7](https://linux-hardware.org/?probe=d7926809d7) | Sep 25, 2023 |
| HP            | Presario CQ43               | [c206dc84ad](https://linux-hardware.org/?probe=c206dc84ad) | Sep 25, 2023 |
| Aquarius      | NS585                       | [e901467e39](https://linux-hardware.org/?probe=e901467e39) | Sep 25, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [ab332c2dcb](https://linux-hardware.org/?probe=ab332c2dcb) | Sep 25, 2023 |
| Acer          | Aspire 5951G                | [4c50b8e9b0](https://linux-hardware.org/?probe=4c50b8e9b0) | Sep 25, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0CN0... | [9c0b702e21](https://linux-hardware.org/?probe=9c0b702e21) | Sep 24, 2023 |
| Dell          | XPS 15 9500                 | [fcff405070](https://linux-hardware.org/?probe=fcff405070) | Sep 24, 2023 |
| Dell          | XPS 15 9500                 | [5bedca0fe9](https://linux-hardware.org/?probe=5bedca0fe9) | Sep 24, 2023 |
| Valve         | Jupiter                     | [36fd2d4d96](https://linux-hardware.org/?probe=36fd2d4d96) | Sep 24, 2023 |
| Dell          | Latitude 5420               | [0e22f551b9](https://linux-hardware.org/?probe=0e22f551b9) | Sep 24, 2023 |
| HP            | 250 G8 Notebook PC          | [6b3c3ce703](https://linux-hardware.org/?probe=6b3c3ce703) | Sep 23, 2023 |
| HP            | 250 G4                      | [c9dac1b4d5](https://linux-hardware.org/?probe=c9dac1b4d5) | Sep 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [42309ddc8c](https://linux-hardware.org/?probe=42309ddc8c) | Sep 23, 2023 |
| HP            | 250 G8 Notebook PC          | [e2dd7767f0](https://linux-hardware.org/?probe=e2dd7767f0) | Sep 23, 2023 |
| Dell          | Vostro 14-3468              | [0b6bdbbecb](https://linux-hardware.org/?probe=0b6bdbbecb) | Sep 23, 2023 |
| HP            | Compaq Presario CQ60        | [ae8071638f](https://linux-hardware.org/?probe=ae8071638f) | Sep 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [eb276947f2](https://linux-hardware.org/?probe=eb276947f2) | Sep 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [574c2193bb](https://linux-hardware.org/?probe=574c2193bb) | Sep 23, 2023 |
| Acer          | Nitro AN515-58              | [589716b973](https://linux-hardware.org/?probe=589716b973) | Sep 23, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B90... | [e273beb83a](https://linux-hardware.org/?probe=e273beb83a) | Sep 22, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [ad1b8126d2](https://linux-hardware.org/?probe=ad1b8126d2) | Sep 22, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B90... | [0d786ffd74](https://linux-hardware.org/?probe=0d786ffd74) | Sep 22, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [1e9774c53c](https://linux-hardware.org/?probe=1e9774c53c) | Sep 22, 2023 |
| Dell          | Latitude 3320               | [cf413808cb](https://linux-hardware.org/?probe=cf413808cb) | Sep 22, 2023 |
| Dell          | Latitude 3320               | [bd39ee30ac](https://linux-hardware.org/?probe=bd39ee30ac) | Sep 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [e75a2a8b71](https://linux-hardware.org/?probe=e75a2a8b71) | Sep 22, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [c14178c7fa](https://linux-hardware.org/?probe=c14178c7fa) | Sep 22, 2023 |
| Samsung       | R505                        | [8aef37cda9](https://linux-hardware.org/?probe=8aef37cda9) | Sep 22, 2023 |
| ASUSTek       | X555LJ                      | [2edb781d68](https://linux-hardware.org/?probe=2edb781d68) | Sep 22, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [4bf358cd4f](https://linux-hardware.org/?probe=4bf358cd4f) | Sep 22, 2023 |
| HP            | EliteBook 840 G3            | [b6379ef77c](https://linux-hardware.org/?probe=b6379ef77c) | Sep 22, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [ea491d194f](https://linux-hardware.org/?probe=ea491d194f) | Sep 21, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e33bb92eb6](https://linux-hardware.org/?probe=e33bb92eb6) | Sep 21, 2023 |
| Lenovo        | V14 G3 IAP 82TS             | [2528381c0e](https://linux-hardware.org/?probe=2528381c0e) | Sep 21, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [f9430fd075](https://linux-hardware.org/?probe=f9430fd075) | Sep 21, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e337cc85e5](https://linux-hardware.org/?probe=e337cc85e5) | Sep 20, 2023 |
| Acer          | Aspire E1-531               | [f0173f0458](https://linux-hardware.org/?probe=f0173f0458) | Sep 20, 2023 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | [228d31bf59](https://linux-hardware.org/?probe=228d31bf59) | Sep 20, 2023 |
| Dell          | XPS 13 9300                 | [49bb68e979](https://linux-hardware.org/?probe=49bb68e979) | Sep 20, 2023 |
| HP            | ProBook 450 G1              | [4e5ae95013](https://linux-hardware.org/?probe=4e5ae95013) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | [c34d9b9514](https://linux-hardware.org/?probe=c34d9b9514) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | [7ec3567855](https://linux-hardware.org/?probe=7ec3567855) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | [676dd13401](https://linux-hardware.org/?probe=676dd13401) | Sep 20, 2023 |
| Dell          | Precision 5560              | [456e9e2c78](https://linux-hardware.org/?probe=456e9e2c78) | Sep 20, 2023 |
| Lenovo        | ThinkPad L420 78564ES       | [a6f3af802d](https://linux-hardware.org/?probe=a6f3af802d) | Sep 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5662d8f95c](https://linux-hardware.org/?probe=5662d8f95c) | Sep 20, 2023 |
| Dell          | Precision 7550              | [75394df91f](https://linux-hardware.org/?probe=75394df91f) | Sep 19, 2023 |
| HP            | Laptop 15-bs0xx             | [963330511d](https://linux-hardware.org/?probe=963330511d) | Sep 19, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [a5f79b33f4](https://linux-hardware.org/?probe=a5f79b33f4) | Sep 19, 2023 |
| Notebook      | P7xxDM3(-G)                 | [b302c7b008](https://linux-hardware.org/?probe=b302c7b008) | Sep 19, 2023 |
| Lenovo        | ThinkPad X61s 7666Y2X       | [177e40808d](https://linux-hardware.org/?probe=177e40808d) | Sep 19, 2023 |
| Notebook      | P7xxDM3(-G)                 | [ec386099b2](https://linux-hardware.org/?probe=ec386099b2) | Sep 19, 2023 |
| HP            | Laptop 17-cp0xxx            | [05e3350e1f](https://linux-hardware.org/?probe=05e3350e1f) | Sep 19, 2023 |
| Dell          | XPS 13 9360                 | [149f246bd7](https://linux-hardware.org/?probe=149f246bd7) | Sep 19, 2023 |
| Acer          | Aspire A515-56              | [db16273e72](https://linux-hardware.org/?probe=db16273e72) | Sep 19, 2023 |
| Intel Clie... | LAPBC710                    | [af446fcb4d](https://linux-hardware.org/?probe=af446fcb4d) | Sep 19, 2023 |
| Intel Clie... | LAPBC710                    | [eae124fa61](https://linux-hardware.org/?probe=eae124fa61) | Sep 19, 2023 |
| HP            | Laptop 15-bs0xx             | [5f8df7dfcb](https://linux-hardware.org/?probe=5f8df7dfcb) | Sep 19, 2023 |
| Dell          | Latitude E6430              | [d83d7bbfa8](https://linux-hardware.org/?probe=d83d7bbfa8) | Sep 18, 2023 |
| HP            | 15                          | [b016d5ee79](https://linux-hardware.org/?probe=b016d5ee79) | Sep 18, 2023 |
| Lenovo        | Z50-75 80EC                 | [410df263b8](https://linux-hardware.org/?probe=410df263b8) | Sep 18, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [ebfe5ca0b0](https://linux-hardware.org/?probe=ebfe5ca0b0) | Sep 18, 2023 |
| Acer          | Extensa 215-32              | [6879449933](https://linux-hardware.org/?probe=6879449933) | Sep 18, 2023 |
| Aquarius      | NS585                       | [6ac8bd5909](https://linux-hardware.org/?probe=6ac8bd5909) | Sep 18, 2023 |
| Lenovo        | Z50-75 80EC                 | [e14140ad96](https://linux-hardware.org/?probe=e14140ad96) | Sep 18, 2023 |
| HP            | Mini 110-1000               | [dda4d7a910](https://linux-hardware.org/?probe=dda4d7a910) | Sep 18, 2023 |
| HP            | Mini 110-1000               | [ee2d142228](https://linux-hardware.org/?probe=ee2d142228) | Sep 18, 2023 |
| Acer          | TravelMate P446-MG          | [08d9d6868b](https://linux-hardware.org/?probe=08d9d6868b) | Sep 17, 2023 |
| Google        | Droid                       | [e0a0628d0a](https://linux-hardware.org/?probe=e0a0628d0a) | Sep 17, 2023 |
| HP            | Compaq Mini 311-1100        | [8bdfb6307c](https://linux-hardware.org/?probe=8bdfb6307c) | Sep 17, 2023 |
| HP            | Laptop 15-dw3xxx            | [f84a480b09](https://linux-hardware.org/?probe=f84a480b09) | Sep 17, 2023 |
| Dell          | XPS 13 9370                 | [7715522f7f](https://linux-hardware.org/?probe=7715522f7f) | Sep 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [cda370cdc3](https://linux-hardware.org/?probe=cda370cdc3) | Sep 16, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | [b7c1a0a0a0](https://linux-hardware.org/?probe=b7c1a0a0a0) | Sep 16, 2023 |
| Apple         | MacBookPro8,1               | [c3791ba730](https://linux-hardware.org/?probe=c3791ba730) | Sep 16, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | [f5884967d0](https://linux-hardware.org/?probe=f5884967d0) | Sep 16, 2023 |
| Dell          | Latitude E5570              | [fd5ba4aa5a](https://linux-hardware.org/?probe=fd5ba4aa5a) | Sep 15, 2023 |
| Dell          | Precision 5570              | [8b3c21b110](https://linux-hardware.org/?probe=8b3c21b110) | Sep 15, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | [66b29aeb1d](https://linux-hardware.org/?probe=66b29aeb1d) | Sep 15, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | [3eb787f2ec](https://linux-hardware.org/?probe=3eb787f2ec) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [eaa723190d](https://linux-hardware.org/?probe=eaa723190d) | Sep 15, 2023 |
| ASUSTek       | X507UB                      | [ca19710375](https://linux-hardware.org/?probe=ca19710375) | Sep 15, 2023 |
| ASUSTek       | X751LN                      | [77ecc965aa](https://linux-hardware.org/?probe=77ecc965aa) | Sep 14, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0ffb2a765f](https://linux-hardware.org/?probe=0ffb2a765f) | Sep 14, 2023 |
| Toshiba       | PORTEGE Z830                | [a3e1ac295c](https://linux-hardware.org/?probe=a3e1ac295c) | Sep 14, 2023 |
| ASUSTek       | P553UJ                      | [3463413300](https://linux-hardware.org/?probe=3463413300) | Sep 14, 2023 |
| Toshiba       | PORTEGE Z830                | [6f4c4a4120](https://linux-hardware.org/?probe=6f4c4a4120) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [d27fa5404b](https://linux-hardware.org/?probe=d27fa5404b) | Sep 14, 2023 |
| Dell          | Latitude 5440               | [93a296a628](https://linux-hardware.org/?probe=93a296a628) | Sep 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [033eca4030](https://linux-hardware.org/?probe=033eca4030) | Sep 14, 2023 |
| HP            | 245 G7 Notebook PC          | [ab68dea087](https://linux-hardware.org/?probe=ab68dea087) | Sep 14, 2023 |
| HP            | ProBook 6570b               | [fc5c01d215](https://linux-hardware.org/?probe=fc5c01d215) | Sep 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [0cdeaab8be](https://linux-hardware.org/?probe=0cdeaab8be) | Sep 13, 2023 |
| MSI           | GS66 Stealth 11UG           | [304abac74b](https://linux-hardware.org/?probe=304abac74b) | Sep 13, 2023 |
| HP            | Stream Notebook PC 11       | [f4c5ae4297](https://linux-hardware.org/?probe=f4c5ae4297) | Sep 13, 2023 |
| Acer          | AOA150                      | [bc32c4814d](https://linux-hardware.org/?probe=bc32c4814d) | Sep 13, 2023 |
| Lenovo        | ThinkPad X230 232036U       | [58ec12094c](https://linux-hardware.org/?probe=58ec12094c) | Sep 13, 2023 |
| Google        | Cave                        | [74c8e00b23](https://linux-hardware.org/?probe=74c8e00b23) | Sep 13, 2023 |
| Dell          | Latitude E6430              | [79cf77c6ba](https://linux-hardware.org/?probe=79cf77c6ba) | Sep 12, 2023 |
| Dell          | Latitude E7470              | [4f2094dfef](https://linux-hardware.org/?probe=4f2094dfef) | Sep 12, 2023 |
| Toshiba       | Satellite L640              | [ac5a264fea](https://linux-hardware.org/?probe=ac5a264fea) | Sep 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [be2af85bb7](https://linux-hardware.org/?probe=be2af85bb7) | Sep 12, 2023 |
| SLIMBOOK      | Essential15L                | [92dbc92137](https://linux-hardware.org/?probe=92dbc92137) | Sep 12, 2023 |
| HUAWEI        | BOM-WXX9                    | [0224dfd46f](https://linux-hardware.org/?probe=0224dfd46f) | Sep 11, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [52b50b0d68](https://linux-hardware.org/?probe=52b50b0d68) | Sep 11, 2023 |
| Google        | Enguarde                    | [4fd827adc5](https://linux-hardware.org/?probe=4fd827adc5) | Sep 11, 2023 |
| Google        | Enguarde                    | [b2b5b5f73b](https://linux-hardware.org/?probe=b2b5b5f73b) | Sep 11, 2023 |
| Lenovo        | ThinkPad L380 20M50013GE    | [e7778dd80d](https://linux-hardware.org/?probe=e7778dd80d) | Sep 11, 2023 |
| HP            | 250 G3                      | [162574954f](https://linux-hardware.org/?probe=162574954f) | Sep 11, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [24e256ad9e](https://linux-hardware.org/?probe=24e256ad9e) | Sep 11, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [57e8f1b556](https://linux-hardware.org/?probe=57e8f1b556) | Sep 11, 2023 |
| Samsung       | 550XED                      | [69d754d35b](https://linux-hardware.org/?probe=69d754d35b) | Sep 11, 2023 |
| Samsung       | 550XED                      | [8187eca3e3](https://linux-hardware.org/?probe=8187eca3e3) | Sep 11, 2023 |
| Panasonic     | CF-19RHR3DPM                | [11484f2d00](https://linux-hardware.org/?probe=11484f2d00) | Sep 10, 2023 |
| ASUSTek       | G751JT                      | [4395b1ccb2](https://linux-hardware.org/?probe=4395b1ccb2) | Sep 10, 2023 |
| Dell          | Precision 5530              | [7e0e7dca27](https://linux-hardware.org/?probe=7e0e7dca27) | Sep 10, 2023 |
| ASUSTek       | X550VX                      | [b1b59ca70c](https://linux-hardware.org/?probe=b1b59ca70c) | Sep 10, 2023 |
| Acer          | Extensa 5220                | [c4ea757260](https://linux-hardware.org/?probe=c4ea757260) | Sep 10, 2023 |
| HP            | Unknown                     | [cb5704a65f](https://linux-hardware.org/?probe=cb5704a65f) | Sep 10, 2023 |
| Google        | Lillipup                    | [c3a892cdca](https://linux-hardware.org/?probe=c3a892cdca) | Sep 10, 2023 |
| HP            | ProBook 6570b               | [3ed768081c](https://linux-hardware.org/?probe=3ed768081c) | Sep 09, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [780a68ac11](https://linux-hardware.org/?probe=780a68ac11) | Sep 09, 2023 |
| Acer          | Aspire E1-531               | [91decda3c9](https://linux-hardware.org/?probe=91decda3c9) | Sep 09, 2023 |
| Dell          | Inspiron 7580               | [9705f02462](https://linux-hardware.org/?probe=9705f02462) | Sep 09, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [3865278574](https://linux-hardware.org/?probe=3865278574) | Sep 09, 2023 |
| Acer          | Nitro AN515-55              | [3f247b15c6](https://linux-hardware.org/?probe=3f247b15c6) | Sep 09, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005QU... | [0a57a98442](https://linux-hardware.org/?probe=0a57a98442) | Sep 09, 2023 |
| Lenovo        | ThinkPad X395 20NMS0YG00    | [b3697e5a7e](https://linux-hardware.org/?probe=b3697e5a7e) | Sep 09, 2023 |
| Google        | Enguarde                    | [3ec3cf816b](https://linux-hardware.org/?probe=3ec3cf816b) | Sep 08, 2023 |
| Google        | Enguarde                    | [fa7b318083](https://linux-hardware.org/?probe=fa7b318083) | Sep 08, 2023 |
| Google        | Enguarde                    | [1621463a03](https://linux-hardware.org/?probe=1621463a03) | Sep 08, 2023 |
| Google        | Enguarde                    | [b54a785396](https://linux-hardware.org/?probe=b54a785396) | Sep 08, 2023 |
| Google        | Enguarde                    | [b35f66260b](https://linux-hardware.org/?probe=b35f66260b) | Sep 08, 2023 |
| Google        | Enguarde                    | [e754c23dd9](https://linux-hardware.org/?probe=e754c23dd9) | Sep 08, 2023 |
| Google        | Enguarde                    | [71e3d1a632](https://linux-hardware.org/?probe=71e3d1a632) | Sep 08, 2023 |
| Google        | Enguarde                    | [352198bb3c](https://linux-hardware.org/?probe=352198bb3c) | Sep 08, 2023 |
| Google        | Enguarde                    | [15edd97e90](https://linux-hardware.org/?probe=15edd97e90) | Sep 08, 2023 |
| Google        | Enguarde                    | [265336497a](https://linux-hardware.org/?probe=265336497a) | Sep 08, 2023 |
| Google        | Enguarde                    | [af54a959e3](https://linux-hardware.org/?probe=af54a959e3) | Sep 08, 2023 |
| Google        | Enguarde                    | [d102cf6258](https://linux-hardware.org/?probe=d102cf6258) | Sep 08, 2023 |
| Google        | Enguarde                    | [d6fd89750c](https://linux-hardware.org/?probe=d6fd89750c) | Sep 08, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [4e756a7c7d](https://linux-hardware.org/?probe=4e756a7c7d) | Sep 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e0899f8743](https://linux-hardware.org/?probe=e0899f8743) | Sep 08, 2023 |
| Dell          | Latitude 5530               | [ae835c8d8b](https://linux-hardware.org/?probe=ae835c8d8b) | Sep 08, 2023 |
| HP            | 250 G3                      | [51ef1d34d0](https://linux-hardware.org/?probe=51ef1d34d0) | Sep 08, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [c9d6171716](https://linux-hardware.org/?probe=c9d6171716) | Sep 08, 2023 |
| HP            | Compaq Presario CQ40        | [4695b758c9](https://linux-hardware.org/?probe=4695b758c9) | Sep 08, 2023 |
| HP            | Compaq Presario CQ40        | [e8a4fb3aea](https://linux-hardware.org/?probe=e8a4fb3aea) | Sep 08, 2023 |
| Dell          | Latitude E5550              | [90fc999e4a](https://linux-hardware.org/?probe=90fc999e4a) | Sep 08, 2023 |
| ASUSTek       | X507UB                      | [4604e73045](https://linux-hardware.org/?probe=4604e73045) | Sep 08, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [b05fdf4d62](https://linux-hardware.org/?probe=b05fdf4d62) | Sep 08, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [db6d9f2293](https://linux-hardware.org/?probe=db6d9f2293) | Sep 08, 2023 |
| Lenovo        | ThinkPad P43s 20RH001UMX    | [0fdff74089](https://linux-hardware.org/?probe=0fdff74089) | Sep 07, 2023 |
| Google        | Enguarde                    | [7718db84e9](https://linux-hardware.org/?probe=7718db84e9) | Sep 07, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [9117a08473](https://linux-hardware.org/?probe=9117a08473) | Sep 07, 2023 |
| Google        | Enguarde                    | [8a82984679](https://linux-hardware.org/?probe=8a82984679) | Sep 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e2f9ce90d3](https://linux-hardware.org/?probe=e2f9ce90d3) | Sep 07, 2023 |
| ASUSTek       | N751JX                      | [8ece217753](https://linux-hardware.org/?probe=8ece217753) | Sep 06, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [0468bc91fc](https://linux-hardware.org/?probe=0468bc91fc) | Sep 06, 2023 |
| ASUSTek       | X542UQ                      | [50ecc5159c](https://linux-hardware.org/?probe=50ecc5159c) | Sep 06, 2023 |
| ASUSTek       | X542UQ                      | [b34e0e7866](https://linux-hardware.org/?probe=b34e0e7866) | Sep 06, 2023 |
| Acer          | Aspire E1-531               | [9d5880bc6c](https://linux-hardware.org/?probe=9d5880bc6c) | Sep 06, 2023 |
| Acer          | Aspire E1-531               | [6ffc334cf9](https://linux-hardware.org/?probe=6ffc334cf9) | Sep 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | [03f6b3b62b](https://linux-hardware.org/?probe=03f6b3b62b) | Sep 06, 2023 |
| Toshiba       | Satellite A205              | [9a44e74608](https://linux-hardware.org/?probe=9a44e74608) | Sep 06, 2023 |
| Toshiba       | Satellite A205              | [a2b456886d](https://linux-hardware.org/?probe=a2b456886d) | Sep 05, 2023 |
| HP            | ZBook 15 G3                 | [faac131992](https://linux-hardware.org/?probe=faac131992) | Sep 05, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [1bcf7b95c6](https://linux-hardware.org/?probe=1bcf7b95c6) | Sep 05, 2023 |
| Lenovo        | ThinkPad T490 20N2001YUS    | [75c15ac2e8](https://linux-hardware.org/?probe=75c15ac2e8) | Sep 05, 2023 |
| ASUSTek       | K53SD                       | [051fefc7ca](https://linux-hardware.org/?probe=051fefc7ca) | Sep 05, 2023 |
| Lenovo        | ThinkPad T520 4243WCR       | [181ef642cd](https://linux-hardware.org/?probe=181ef642cd) | Sep 05, 2023 |
| Sony          | VGN-CS108D                  | [24bf5bb06c](https://linux-hardware.org/?probe=24bf5bb06c) | Sep 05, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [eb05baece5](https://linux-hardware.org/?probe=eb05baece5) | Sep 05, 2023 |
| HUAWEI        | NBD-WXX9                    | [005ebd39ce](https://linux-hardware.org/?probe=005ebd39ce) | Sep 05, 2023 |
| ASUSTek       | X541NC                      | [927ba04557](https://linux-hardware.org/?probe=927ba04557) | Sep 05, 2023 |
| Acer          | Aspire E1-531               | [7f9460a97c](https://linux-hardware.org/?probe=7f9460a97c) | Sep 04, 2023 |
| eMachines     | Rhine V1.42                 | [c18c4d64bd](https://linux-hardware.org/?probe=c18c4d64bd) | Sep 04, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [f7a6b9d479](https://linux-hardware.org/?probe=f7a6b9d479) | Sep 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d075cbe2e0](https://linux-hardware.org/?probe=d075cbe2e0) | Sep 04, 2023 |
| Acer          | Aspire ES1-533              | [9c788645a1](https://linux-hardware.org/?probe=9c788645a1) | Sep 03, 2023 |
| ASUSTek       | X507UB                      | [e74c3ad568](https://linux-hardware.org/?probe=e74c3ad568) | Sep 03, 2023 |
| HP            | EliteBook 2740p             | [c6d9dc5a3b](https://linux-hardware.org/?probe=c6d9dc5a3b) | Sep 03, 2023 |
| Dell          | Latitude 5414               | [704d861366](https://linux-hardware.org/?probe=704d861366) | Sep 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [526a6826ab](https://linux-hardware.org/?probe=526a6826ab) | Sep 03, 2023 |
| Google        | Droid                       | [da26431a82](https://linux-hardware.org/?probe=da26431a82) | Sep 03, 2023 |
| Google        | Droid                       | [278861e9e8](https://linux-hardware.org/?probe=278861e9e8) | Sep 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S2KV20    | [248ef69016](https://linux-hardware.org/?probe=248ef69016) | Sep 03, 2023 |
| Acer          | Aspire A515-56              | [435cb2d610](https://linux-hardware.org/?probe=435cb2d610) | Sep 03, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [7ba8b58ea7](https://linux-hardware.org/?probe=7ba8b58ea7) | Sep 03, 2023 |
| Toshiba       | Satellite L10W-B-101        | [1865cdf1ad](https://linux-hardware.org/?probe=1865cdf1ad) | Sep 02, 2023 |
| HP            | ZBook 15 G2                 | [d20f8f324d](https://linux-hardware.org/?probe=d20f8f324d) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [d00f64dfcf](https://linux-hardware.org/?probe=d00f64dfcf) | Sep 02, 2023 |
| Samsung       | RF511/RF411/RF711           | [ab39767c20](https://linux-hardware.org/?probe=ab39767c20) | Sep 02, 2023 |
| Dell          | Latitude E6520              | [b53cd78958](https://linux-hardware.org/?probe=b53cd78958) | Sep 02, 2023 |
| Lenovo        | G505 20240                  | [ea15ab596a](https://linux-hardware.org/?probe=ea15ab596a) | Sep 02, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [155023d91f](https://linux-hardware.org/?probe=155023d91f) | Sep 02, 2023 |
| Lenovo        | Legion 5 15ACH6 82QJ        | [5897684d9e](https://linux-hardware.org/?probe=5897684d9e) | Sep 02, 2023 |
| Dell          | Latitude 5430               | [7a9eb9995d](https://linux-hardware.org/?probe=7a9eb9995d) | Sep 02, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [52e8a720ba](https://linux-hardware.org/?probe=52e8a720ba) | Sep 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [062f19958d](https://linux-hardware.org/?probe=062f19958d) | Sep 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [af78cafb1a](https://linux-hardware.org/?probe=af78cafb1a) | Sep 01, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [5db10955f8](https://linux-hardware.org/?probe=5db10955f8) | Sep 01, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f98a2afc33](https://linux-hardware.org/?probe=f98a2afc33) | Aug 31, 2023 |
| Acer          | Swift SF314-42              | [80bebab849](https://linux-hardware.org/?probe=80bebab849) | Aug 31, 2023 |
| Google        | Enguarde                    | [d67a18c110](https://linux-hardware.org/?probe=d67a18c110) | Aug 30, 2023 |
| HP            | ProBook 6460b               | [18deeb6be6](https://linux-hardware.org/?probe=18deeb6be6) | Aug 30, 2023 |
| GPU Compan... | GWTN156-9                   | [4c8ea16ab2](https://linux-hardware.org/?probe=4c8ea16ab2) | Aug 30, 2023 |
| HP            | Laptop 15s-fq2xxx           | [6d85c1d397](https://linux-hardware.org/?probe=6d85c1d397) | Aug 30, 2023 |
| Acer          | Aspire A515-57              | [c9a61f810d](https://linux-hardware.org/?probe=c9a61f810d) | Aug 30, 2023 |
| Acer          | Aspire A515-57              | [d6fded6169](https://linux-hardware.org/?probe=d6fded6169) | Aug 30, 2023 |
| Google        | Enguarde                    | [08ff2764b2](https://linux-hardware.org/?probe=08ff2764b2) | Aug 30, 2023 |
| Unknown       | Unknown                     | [3718299cea](https://linux-hardware.org/?probe=3718299cea) | Aug 29, 2023 |
| Google        | Enguarde                    | [e2e5a3dadc](https://linux-hardware.org/?probe=e2e5a3dadc) | Aug 29, 2023 |
| Google        | Enguarde                    | [e7a59ac286](https://linux-hardware.org/?probe=e7a59ac286) | Aug 29, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [4bdfa8b9ea](https://linux-hardware.org/?probe=4bdfa8b9ea) | Aug 29, 2023 |
| HP            | EliteBook 845 14 inch G9... | [41ce572b6d](https://linux-hardware.org/?probe=41ce572b6d) | Aug 29, 2023 |
| Acer          | Swift SF314-512             | [a41a08d4ae](https://linux-hardware.org/?probe=a41a08d4ae) | Aug 29, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [62ff88eaf7](https://linux-hardware.org/?probe=62ff88eaf7) | Aug 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CBA... | [243b20df85](https://linux-hardware.org/?probe=243b20df85) | Aug 28, 2023 |
| Lenovo        | ThinkPad E470 20H2S00700    | [cea73826dc](https://linux-hardware.org/?probe=cea73826dc) | Aug 28, 2023 |
| win elemen... | MoreFine S500+              | [9675488adc](https://linux-hardware.org/?probe=9675488adc) | Aug 28, 2023 |
| win elemen... | MoreFine S500+              | [29e062fb36](https://linux-hardware.org/?probe=29e062fb36) | Aug 27, 2023 |
| Apple         | MacBookPro6,2               | [e25e18e9b1](https://linux-hardware.org/?probe=e25e18e9b1) | Aug 27, 2023 |
| Lenovo        | B590 20208                  | [65bf0970da](https://linux-hardware.org/?probe=65bf0970da) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [5ef3048a11](https://linux-hardware.org/?probe=5ef3048a11) | Aug 26, 2023 |
| Dell          | Latitude E6420              | [ae48a8c618](https://linux-hardware.org/?probe=ae48a8c618) | Aug 26, 2023 |
| MSI           | GP76 Leopard 11UG           | [5de726089b](https://linux-hardware.org/?probe=5de726089b) | Aug 26, 2023 |
| Lenovo        | ThinkPad W540 20BG0016US    | [3b5476180b](https://linux-hardware.org/?probe=3b5476180b) | Aug 26, 2023 |
| Alienware     | m16 R1                      | [75f20a1519](https://linux-hardware.org/?probe=75f20a1519) | Aug 26, 2023 |
| Alienware     | m16 R1                      | [89cffc75ea](https://linux-hardware.org/?probe=89cffc75ea) | Aug 26, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [4ca70b63ef](https://linux-hardware.org/?probe=4ca70b63ef) | Aug 25, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [c288ff6b78](https://linux-hardware.org/?probe=c288ff6b78) | Aug 25, 2023 |
| HP            | Pavilion dv5                | [8e621682ec](https://linux-hardware.org/?probe=8e621682ec) | Aug 25, 2023 |
| Acer          | Aspire VN7-793G             | [5d748b1e22](https://linux-hardware.org/?probe=5d748b1e22) | Aug 25, 2023 |
| Acer          | TravelMate P215-53          | [113a5418ca](https://linux-hardware.org/?probe=113a5418ca) | Aug 25, 2023 |
| Acer          | TravelMate P215-53          | [b2579f594d](https://linux-hardware.org/?probe=b2579f594d) | Aug 25, 2023 |
| MSI           | GS65 Stealth Thin 8RE       | [b53212efce](https://linux-hardware.org/?probe=b53212efce) | Aug 24, 2023 |
| Dell          | XPS 9320                    | [1ba8e13634](https://linux-hardware.org/?probe=1ba8e13634) | Aug 24, 2023 |
| ASUSTek       | X450LD                      | [b9187b37b7](https://linux-hardware.org/?probe=b9187b37b7) | Aug 24, 2023 |
| Acer          | Aspire 7741                 | [648f667e11](https://linux-hardware.org/?probe=648f667e11) | Aug 24, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [4d1d53f6d8](https://linux-hardware.org/?probe=4d1d53f6d8) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [5a6247f9b2](https://linux-hardware.org/?probe=5a6247f9b2) | Aug 24, 2023 |
| HP            | Laptop 17-by4xxx            | [9fd582b91e](https://linux-hardware.org/?probe=9fd582b91e) | Aug 24, 2023 |
| HP            | ZBook 14 G2                 | [fcbebfc95a](https://linux-hardware.org/?probe=fcbebfc95a) | Aug 23, 2023 |
| Acer          | Aspire ES1-311              | [93f204808e](https://linux-hardware.org/?probe=93f204808e) | Aug 23, 2023 |
| Lenovo        | IdeaPad Z485 20151          | [599346f806](https://linux-hardware.org/?probe=599346f806) | Aug 23, 2023 |
| Panasonic     | CFMX4-1                     | [fd352acae8](https://linux-hardware.org/?probe=fd352acae8) | Aug 23, 2023 |
| Acer          | TravelMate P214-52          | [6d7eeef62a](https://linux-hardware.org/?probe=6d7eeef62a) | Aug 23, 2023 |
| Acer          | TravelMate P214-52          | [0a000435ae](https://linux-hardware.org/?probe=0a000435ae) | Aug 23, 2023 |
| MSI           | Stealth 17Studio A13VF      | [ca952946e9](https://linux-hardware.org/?probe=ca952946e9) | Aug 23, 2023 |
| ASUSTek       | X507UB                      | [6c8e9739d4](https://linux-hardware.org/?probe=6c8e9739d4) | Aug 23, 2023 |
| Gigabyte      | AORUS 5 KE                  | [abfb96067f](https://linux-hardware.org/?probe=abfb96067f) | Aug 23, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [3e831762f2](https://linux-hardware.org/?probe=3e831762f2) | Aug 22, 2023 |
| Positivo      | Mobile                      | [e39dbd02a9](https://linux-hardware.org/?probe=e39dbd02a9) | Aug 22, 2023 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [8b219ffa3b](https://linux-hardware.org/?probe=8b219ffa3b) | Aug 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [b460d0aa2d](https://linux-hardware.org/?probe=b460d0aa2d) | Aug 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [285b51551c](https://linux-hardware.org/?probe=285b51551c) | Aug 22, 2023 |
| Samsung       | 905S3G/906S3G/915S3G        | [ae599c9d4b](https://linux-hardware.org/?probe=ae599c9d4b) | Aug 22, 2023 |
| ASUSTek       | ROG Strix G531GU_G531GU     | [627606b933](https://linux-hardware.org/?probe=627606b933) | Aug 22, 2023 |
| HP            | Laptop 15z-ef3xxx           | [cf603a20c0](https://linux-hardware.org/?probe=cf603a20c0) | Aug 22, 2023 |
| Sony          | SVE14123CBW                 | [b7891b51b2](https://linux-hardware.org/?probe=b7891b51b2) | Aug 21, 2023 |
| Sony          | SVE14123CBW                 | [9730d7f8f5](https://linux-hardware.org/?probe=9730d7f8f5) | Aug 21, 2023 |
| HP            | 250 G7 Notebook PC          | [cb4da51551](https://linux-hardware.org/?probe=cb4da51551) | Aug 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [0baece8878](https://linux-hardware.org/?probe=0baece8878) | Aug 21, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [43d120af0e](https://linux-hardware.org/?probe=43d120af0e) | Aug 21, 2023 |
| Dell          | Inspiron 15 3515            | [534e1dc3e5](https://linux-hardware.org/?probe=534e1dc3e5) | Aug 21, 2023 |
| Sony          | VPCEH2J9R                   | [a919beee79](https://linux-hardware.org/?probe=a919beee79) | Aug 21, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [e2c346429e](https://linux-hardware.org/?probe=e2c346429e) | Aug 21, 2023 |
| Acer          | Aspire A517-53G             | [692bd3fa37](https://linux-hardware.org/?probe=692bd3fa37) | Aug 20, 2023 |
| Acer          | Aspire A517-53G             | [6313b3f69e](https://linux-hardware.org/?probe=6313b3f69e) | Aug 20, 2023 |
| Dell          | Latitude E5550              | [0f3afef2ac](https://linux-hardware.org/?probe=0f3afef2ac) | Aug 20, 2023 |
| Valve         | Jupiter                     | [36e4b2146b](https://linux-hardware.org/?probe=36e4b2146b) | Aug 20, 2023 |
| EUROCOM       | RACER 2.0                   | [b27f687c16](https://linux-hardware.org/?probe=b27f687c16) | Aug 20, 2023 |
| Acer          | Aspire A515-56              | [501ee4caf7](https://linux-hardware.org/?probe=501ee4caf7) | Aug 20, 2023 |
| Apple         | MacBookAir7,2               | [fb3c8c793c](https://linux-hardware.org/?probe=fb3c8c793c) | Aug 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ab5bc08964](https://linux-hardware.org/?probe=ab5bc08964) | Aug 19, 2023 |
| Dell          | Vostro 3501                 | [5369c283ad](https://linux-hardware.org/?probe=5369c283ad) | Aug 18, 2023 |
| Acer          | Extensa 5235                | [1dc9843f33](https://linux-hardware.org/?probe=1dc9843f33) | Aug 18, 2023 |
| Acer          | Aspire VN7-793G             | [b88e1a5605](https://linux-hardware.org/?probe=b88e1a5605) | Aug 18, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [95c536cff4](https://linux-hardware.org/?probe=95c536cff4) | Aug 18, 2023 |
| ASUSTek       | M3N                         | [7c4b9386db](https://linux-hardware.org/?probe=7c4b9386db) | Aug 18, 2023 |
| Lenovo        | ThinkPad T430s 2355C33      | [4c589a0320](https://linux-hardware.org/?probe=4c589a0320) | Aug 18, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [e66c463188](https://linux-hardware.org/?probe=e66c463188) | Aug 18, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [55b9d87888](https://linux-hardware.org/?probe=55b9d87888) | Aug 18, 2023 |
| HP            | Laptop 15-dy0xxx            | [f938725821](https://linux-hardware.org/?probe=f938725821) | Aug 18, 2023 |
| Alienware     | 17 R4                       | [c16cb58f29](https://linux-hardware.org/?probe=c16cb58f29) | Aug 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [748298f0c8](https://linux-hardware.org/?probe=748298f0c8) | Aug 18, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [24a295f95b](https://linux-hardware.org/?probe=24a295f95b) | Aug 17, 2023 |
| Lenovo        | ThinkPad X220 4291MW5       | [adf4aceec8](https://linux-hardware.org/?probe=adf4aceec8) | Aug 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c647987aaf](https://linux-hardware.org/?probe=c647987aaf) | Aug 16, 2023 |
| Acer          | Aspire one                  | [47131c09b2](https://linux-hardware.org/?probe=47131c09b2) | Aug 16, 2023 |
| Acer          | Aspire A515-52G             | [2d38a6554a](https://linux-hardware.org/?probe=2d38a6554a) | Aug 16, 2023 |
| Lenovo        | G505s 20255                 | [2486dc323f](https://linux-hardware.org/?probe=2486dc323f) | Aug 16, 2023 |
| Lenovo        | ThinkPad L580 20LW000WGE    | [69e443b8a8](https://linux-hardware.org/?probe=69e443b8a8) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480 20L5S2J200    | [66c997fdec](https://linux-hardware.org/?probe=66c997fdec) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480 20L5S2J200    | [e57e76260c](https://linux-hardware.org/?probe=e57e76260c) | Aug 16, 2023 |
| Google        | Phaser360                   | [3c248cc2c8](https://linux-hardware.org/?probe=3c248cc2c8) | Aug 16, 2023 |
| Dell          | Vostro 3501                 | [c36d4d9de0](https://linux-hardware.org/?probe=c36d4d9de0) | Aug 15, 2023 |
| Acer          | Aspire A315-59              | [901f34e440](https://linux-hardware.org/?probe=901f34e440) | Aug 15, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [268eeb2657](https://linux-hardware.org/?probe=268eeb2657) | Aug 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [4c24f10db4](https://linux-hardware.org/?probe=4c24f10db4) | Aug 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [6242833326](https://linux-hardware.org/?probe=6242833326) | Aug 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [22252eb1d9](https://linux-hardware.org/?probe=22252eb1d9) | Aug 15, 2023 |
| Alienware     | m15 R4                      | [40d4ad1e4f](https://linux-hardware.org/?probe=40d4ad1e4f) | Aug 14, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [72e71d1afc](https://linux-hardware.org/?probe=72e71d1afc) | Aug 14, 2023 |
| Dell          | XPS 13 9360                 | [69b51e3f5a](https://linux-hardware.org/?probe=69b51e3f5a) | Aug 14, 2023 |
| MSI           | Z790 GAMING WIFI            | [95e340d91b](https://linux-hardware.org/?probe=95e340d91b) | Aug 14, 2023 |
| Beelink       | Gemini X                    | [1610652627](https://linux-hardware.org/?probe=1610652627) | Aug 14, 2023 |
| Google        | Blooglet                    | [b9967e65c2](https://linux-hardware.org/?probe=b9967e65c2) | Aug 14, 2023 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [57af1d89d6](https://linux-hardware.org/?probe=57af1d89d6) | Aug 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [ab5728ee52](https://linux-hardware.org/?probe=ab5728ee52) | Aug 13, 2023 |
| ASUSTek       | GL552VW                     | [1d77ac2450](https://linux-hardware.org/?probe=1d77ac2450) | Aug 13, 2023 |
| Lenovo        | ThinkPad W530 24477V0       | [2e09955f2f](https://linux-hardware.org/?probe=2e09955f2f) | Aug 13, 2023 |
| HP            | Pavilion dv5                | [78530d4418](https://linux-hardware.org/?probe=78530d4418) | Aug 13, 2023 |
| Apple         | MacBookPro8,1               | [c7bc7c3f16](https://linux-hardware.org/?probe=c7bc7c3f16) | Aug 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [b0524c4203](https://linux-hardware.org/?probe=b0524c4203) | Aug 13, 2023 |
| ASUSTek       | GL552VW                     | [6986ca63da](https://linux-hardware.org/?probe=6986ca63da) | Aug 12, 2023 |
| Acer          | Swift SF314-512             | [7158f3e437](https://linux-hardware.org/?probe=7158f3e437) | Aug 12, 2023 |
| Dell          | Vostro 3500                 | [2ec62f31c9](https://linux-hardware.org/?probe=2ec62f31c9) | Aug 12, 2023 |
| Dell          | Latitude E6430              | [8037585070](https://linux-hardware.org/?probe=8037585070) | Aug 12, 2023 |
| HP            | ZBook 17 G3                 | [475b07d2dc](https://linux-hardware.org/?probe=475b07d2dc) | Aug 12, 2023 |
| Unknown       | Unknown                     | [2e76349d2c](https://linux-hardware.org/?probe=2e76349d2c) | Aug 12, 2023 |
| Unknown       | Unknown                     | [8d7674c3b3](https://linux-hardware.org/?probe=8d7674c3b3) | Aug 11, 2023 |
| HP            | Pavilion dv5                | [41c7682f98](https://linux-hardware.org/?probe=41c7682f98) | Aug 11, 2023 |
| HP            | Pavilion dv5                | [a8f62e42dc](https://linux-hardware.org/?probe=a8f62e42dc) | Aug 11, 2023 |
| Unknown       | Unknown                     | [a064a2d5fd](https://linux-hardware.org/?probe=a064a2d5fd) | Aug 11, 2023 |
| Dell          | Inspiron 3531               | [0384e8a950](https://linux-hardware.org/?probe=0384e8a950) | Aug 11, 2023 |
| Avell High... | A40 LIV                     | [9bc62c7eec](https://linux-hardware.org/?probe=9bc62c7eec) | Aug 11, 2023 |
| HP            | Laptop 15s-eq2xxx           | [e45562b838](https://linux-hardware.org/?probe=e45562b838) | Aug 10, 2023 |
| ASUSTek       | 1005PE                      | [088a155ec9](https://linux-hardware.org/?probe=088a155ec9) | Aug 10, 2023 |
| Acer          | Swift SF314-512             | [e168ac1e62](https://linux-hardware.org/?probe=e168ac1e62) | Aug 10, 2023 |
| PC Special... | NH5xAx                      | [891b5ec398](https://linux-hardware.org/?probe=891b5ec398) | Aug 10, 2023 |
| Lenovo        | ThinkPad T410 25372E6       | [69c4723b51](https://linux-hardware.org/?probe=69c4723b51) | Aug 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S29D00    | [a728658683](https://linux-hardware.org/?probe=a728658683) | Aug 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c87b299407](https://linux-hardware.org/?probe=c87b299407) | Aug 10, 2023 |
| Acer          | Aspire A515-57              | [b95e28ab5d](https://linux-hardware.org/?probe=b95e28ab5d) | Aug 09, 2023 |
| Lenovo        | G460 20041                  | [709445c691](https://linux-hardware.org/?probe=709445c691) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [72655a5d65](https://linux-hardware.org/?probe=72655a5d65) | Aug 08, 2023 |
| Dell          | Inspiron 7537               | [61093a9af1](https://linux-hardware.org/?probe=61093a9af1) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [965f96493c](https://linux-hardware.org/?probe=965f96493c) | Aug 08, 2023 |
| HONOR         | HYM-WXX                     | [6f5e2be121](https://linux-hardware.org/?probe=6f5e2be121) | Aug 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [c06b23398a](https://linux-hardware.org/?probe=c06b23398a) | Aug 08, 2023 |
| Acer          | Aspire E5-573G              | [305061b67e](https://linux-hardware.org/?probe=305061b67e) | Aug 08, 2023 |
| Avell High... | A40 LIV                     | [4022d66d9a](https://linux-hardware.org/?probe=4022d66d9a) | Aug 08, 2023 |
| Lenovo        | ThinkPad T530 2394EN6       | [d348a65379](https://linux-hardware.org/?probe=d348a65379) | Aug 07, 2023 |
| Echips Imp... | NQ15E                       | [7d5e97a545](https://linux-hardware.org/?probe=7d5e97a545) | Aug 07, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [36c52dfe36](https://linux-hardware.org/?probe=36c52dfe36) | Aug 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [543719cf07](https://linux-hardware.org/?probe=543719cf07) | Aug 07, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [be823adc05](https://linux-hardware.org/?probe=be823adc05) | Aug 07, 2023 |
| Acer          | Aspire V5-121               | [4b8b0f132d](https://linux-hardware.org/?probe=4b8b0f132d) | Aug 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E02    | [a3e3489451](https://linux-hardware.org/?probe=a3e3489451) | Aug 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [7e185ae211](https://linux-hardware.org/?probe=7e185ae211) | Aug 07, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [053d461635](https://linux-hardware.org/?probe=053d461635) | Aug 06, 2023 |
| Apple         | MacBook7,1                  | [38d285144e](https://linux-hardware.org/?probe=38d285144e) | Aug 06, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | [55e9e43f37](https://linux-hardware.org/?probe=55e9e43f37) | Aug 06, 2023 |
| Dell          | Inspiron 5547               | [8f33c0cf28](https://linux-hardware.org/?probe=8f33c0cf28) | Aug 06, 2023 |
| HP            | Presario CQ57               | [cd84f6fa01](https://linux-hardware.org/?probe=cd84f6fa01) | Aug 06, 2023 |
| GPU Compan... | GWNR71517                   | [d754d51977](https://linux-hardware.org/?probe=d754d51977) | Aug 06, 2023 |
| Dell          | Latitude E5440              | [326ba9627a](https://linux-hardware.org/?probe=326ba9627a) | Aug 06, 2023 |
| Dell          | Latitude 5290 2-in-1        | [b4cc5c436c](https://linux-hardware.org/?probe=b4cc5c436c) | Aug 06, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | [89119ae1fc](https://linux-hardware.org/?probe=89119ae1fc) | Aug 06, 2023 |
| HP            | EliteBook 840 G3            | [9c2b1b1da7](https://linux-hardware.org/?probe=9c2b1b1da7) | Aug 06, 2023 |
| Dell          | Inspiron 15 3511            | [217bd70a25](https://linux-hardware.org/?probe=217bd70a25) | Aug 06, 2023 |
| Acer          | Aspire E5-553G              | [39140ff7de](https://linux-hardware.org/?probe=39140ff7de) | Aug 05, 2023 |
| Acer          | Aspire A315-59              | [fc1d6007aa](https://linux-hardware.org/?probe=fc1d6007aa) | Aug 05, 2023 |
| Acer          | Aspire A315-59              | [deff4c99b6](https://linux-hardware.org/?probe=deff4c99b6) | Aug 05, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2f529a830c](https://linux-hardware.org/?probe=2f529a830c) | Aug 05, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [9d00f10bab](https://linux-hardware.org/?probe=9d00f10bab) | Aug 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | [8511f4c245](https://linux-hardware.org/?probe=8511f4c245) | Aug 05, 2023 |
| Acer          | Swift SF314-512             | [ca109297da](https://linux-hardware.org/?probe=ca109297da) | Aug 05, 2023 |
| Sony          | VGN-NS11S_S                 | [8ad31bd20c](https://linux-hardware.org/?probe=8ad31bd20c) | Aug 05, 2023 |
| Shuttle       | DS47D                       | [7d1ceb9b3a](https://linux-hardware.org/?probe=7d1ceb9b3a) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [76662ba2c9](https://linux-hardware.org/?probe=76662ba2c9) | Aug 05, 2023 |
| ASUSTek       | N501JW                      | [e7d254dbe5](https://linux-hardware.org/?probe=e7d254dbe5) | Aug 04, 2023 |
| Dell          | Latitude E6400              | [ca61145546](https://linux-hardware.org/?probe=ca61145546) | Aug 04, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [12948b89f6](https://linux-hardware.org/?probe=12948b89f6) | Aug 04, 2023 |
| HP            | ProBook 640 G2              | [7cacb46425](https://linux-hardware.org/?probe=7cacb46425) | Aug 04, 2023 |
| Dell          | XPS 9320                    | [140f8f8b2e](https://linux-hardware.org/?probe=140f8f8b2e) | Aug 04, 2023 |
| Sony          | VGN-FW373D                  | [535f0edf33](https://linux-hardware.org/?probe=535f0edf33) | Aug 04, 2023 |
| HP            | Lantis                      | [2c917365b3](https://linux-hardware.org/?probe=2c917365b3) | Aug 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [51ad22a795](https://linux-hardware.org/?probe=51ad22a795) | Aug 03, 2023 |
| Dell          | Vostro 3405                 | [db4954c21d](https://linux-hardware.org/?probe=db4954c21d) | Aug 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | [6bc628f4e6](https://linux-hardware.org/?probe=6bc628f4e6) | Aug 03, 2023 |
| Google        | Enguarde                    | [663e44ce58](https://linux-hardware.org/?probe=663e44ce58) | Aug 03, 2023 |
| Dell          | Inspiron 5566               | [21d7f13381](https://linux-hardware.org/?probe=21d7f13381) | Aug 03, 2023 |
| Acer          | Nitro AN515-57              | [cef74aa3cb](https://linux-hardware.org/?probe=cef74aa3cb) | Aug 03, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [1317097350](https://linux-hardware.org/?probe=1317097350) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [8036065591](https://linux-hardware.org/?probe=8036065591) | Aug 03, 2023 |
| Samsung       | 305U1A                      | [f65d34a8fb](https://linux-hardware.org/?probe=f65d34a8fb) | Aug 03, 2023 |
| ASUSTek       | 1015BX                      | [4770dbfc22](https://linux-hardware.org/?probe=4770dbfc22) | Aug 02, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a1f99c3e4d](https://linux-hardware.org/?probe=a1f99c3e4d) | Aug 02, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [433a85501a](https://linux-hardware.org/?probe=433a85501a) | Aug 02, 2023 |
| HP            | EliteBook 840 G3            | [0ae0b35097](https://linux-hardware.org/?probe=0ae0b35097) | Aug 02, 2023 |
| Dell          | Vostro 5515                 | [0e031a4729](https://linux-hardware.org/?probe=0e031a4729) | Aug 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | [2d046d70cc](https://linux-hardware.org/?probe=2d046d70cc) | Aug 02, 2023 |
| Samsung       | 300E5M/300E5L               | [d4c5149060](https://linux-hardware.org/?probe=d4c5149060) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [291bf82303](https://linux-hardware.org/?probe=291bf82303) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [7a9c57ad84](https://linux-hardware.org/?probe=7a9c57ad84) | Aug 02, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [dfb33be517](https://linux-hardware.org/?probe=dfb33be517) | Aug 01, 2023 |
| HP            | EliteBook 840 G3            | [b53d4c2fad](https://linux-hardware.org/?probe=b53d4c2fad) | Aug 01, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [d3250ef8d7](https://linux-hardware.org/?probe=d3250ef8d7) | Aug 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | [4a4ac95dcc](https://linux-hardware.org/?probe=4a4ac95dcc) | Aug 01, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | [1e963cc76b](https://linux-hardware.org/?probe=1e963cc76b) | Aug 01, 2023 |
| ASUSTek       | G750JX                      | [06279baf34](https://linux-hardware.org/?probe=06279baf34) | Aug 01, 2023 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | [a9232da3e4](https://linux-hardware.org/?probe=a9232da3e4) | Jul 31, 2023 |
| Lenovo        | Flex 2-14 20404             | [dd24507513](https://linux-hardware.org/?probe=dd24507513) | Jul 31, 2023 |
| Google        | Kevin                       | [ca1037f6ca](https://linux-hardware.org/?probe=ca1037f6ca) | Jul 31, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [961a4eebbd](https://linux-hardware.org/?probe=961a4eebbd) | Jul 31, 2023 |
| Packard Be... | H17HV                       | [de2003d390](https://linux-hardware.org/?probe=de2003d390) | Jul 31, 2023 |
| HP            | ProBook 640 G2              | [9e297e7c8e](https://linux-hardware.org/?probe=9e297e7c8e) | Jul 31, 2023 |
| Dell          | Inspiron 15 3511            | [3ea3ff2535](https://linux-hardware.org/?probe=3ea3ff2535) | Jul 31, 2023 |
| NEC Comput... | PC-VY22GXZCA                | [180d6cf97d](https://linux-hardware.org/?probe=180d6cf97d) | Jul 31, 2023 |
| Apple         | MacBookAir3,1               | [1859204a6f](https://linux-hardware.org/?probe=1859204a6f) | Jul 31, 2023 |
| Apple         | MacBookPro5,5               | [f201460a34](https://linux-hardware.org/?probe=f201460a34) | Jul 30, 2023 |
| Dell          | Inspiron 5547               | [f3de23350d](https://linux-hardware.org/?probe=f3de23350d) | Jul 30, 2023 |
| Dell          | Inspiron 5547               | [3be466c09c](https://linux-hardware.org/?probe=3be466c09c) | Jul 30, 2023 |
| Apple         | MacBookPro6,2               | [c5205f5512](https://linux-hardware.org/?probe=c5205f5512) | Jul 30, 2023 |
| Dell          | Latitude E5270              | [ae07c57989](https://linux-hardware.org/?probe=ae07c57989) | Jul 30, 2023 |
| Apple         | MacBookPro8,2               | [ffda715e5e](https://linux-hardware.org/?probe=ffda715e5e) | Jul 30, 2023 |
| Apple         | MacBookPro9,1               | [3b030b25ac](https://linux-hardware.org/?probe=3b030b25ac) | Jul 30, 2023 |
| Lenovo        | ThinkPad X220 42914XG       | [053a30cc87](https://linux-hardware.org/?probe=053a30cc87) | Jul 30, 2023 |
| HP            | ProBook 640 G2              | [87a4b835cf](https://linux-hardware.org/?probe=87a4b835cf) | Jul 30, 2023 |
| Lenovo        | ThinkPad Edge E430 32543... | [b30651e46f](https://linux-hardware.org/?probe=b30651e46f) | Jul 30, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0YW0... | [3ff995e8b7](https://linux-hardware.org/?probe=3ff995e8b7) | Jul 30, 2023 |
| ASUSTek       | Zephyrus S GX701GX_GX701... | [69da742061](https://linux-hardware.org/?probe=69da742061) | Jul 30, 2023 |
| Lenovo        | ThinkPad X201 3680BF5       | [dd11ccaaad](https://linux-hardware.org/?probe=dd11ccaaad) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [d1a4b2769a](https://linux-hardware.org/?probe=d1a4b2769a) | Jul 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [d1bf55b135](https://linux-hardware.org/?probe=d1bf55b135) | Jul 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [ea8a893b11](https://linux-hardware.org/?probe=ea8a893b11) | Jul 29, 2023 |
| Sony          | SVS13A1Z9RN                 | [533b3018ea](https://linux-hardware.org/?probe=533b3018ea) | Jul 29, 2023 |
| Acer          | Swift SF315-52G             | [aca997f2b5](https://linux-hardware.org/?probe=aca997f2b5) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [ce140941bc](https://linux-hardware.org/?probe=ce140941bc) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [19850c3ad1](https://linux-hardware.org/?probe=19850c3ad1) | Jul 29, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [7207a12cd1](https://linux-hardware.org/?probe=7207a12cd1) | Jul 29, 2023 |
| Dell          | Latitude 5520               | [5151c4275a](https://linux-hardware.org/?probe=5151c4275a) | Jul 29, 2023 |
| VALE          | Notebook Classic C140       | [ec65662265](https://linux-hardware.org/?probe=ec65662265) | Jul 28, 2023 |
| HP            | Pavilion Gaming Laptop      | [b277fcda26](https://linux-hardware.org/?probe=b277fcda26) | Jul 28, 2023 |
| HP            | Victus by Gaming Laptop ... | [7595472fb4](https://linux-hardware.org/?probe=7595472fb4) | Jul 28, 2023 |
| Dell          | Latitude 7480               | [4287f8186f](https://linux-hardware.org/?probe=4287f8186f) | Jul 28, 2023 |
| Chitech Sh... | Tibuta_MasterPad-W100       | [202a9be7b7](https://linux-hardware.org/?probe=202a9be7b7) | Jul 28, 2023 |
| Casper        | EXCALIBUR G770              | [1b416b9f01](https://linux-hardware.org/?probe=1b416b9f01) | Jul 28, 2023 |
| Dell          | Precision 3520              | [bc2e0ff018](https://linux-hardware.org/?probe=bc2e0ff018) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [9cbedced8b](https://linux-hardware.org/?probe=9cbedced8b) | Jul 28, 2023 |
| Dell          | System XPS L702X            | [5e9f83aa10](https://linux-hardware.org/?probe=5e9f83aa10) | Jul 28, 2023 |
| Acer          | Aspire A315-21G             | [0a4e1c4510](https://linux-hardware.org/?probe=0a4e1c4510) | Jul 28, 2023 |
| Apple         | MacBookPro5,2               | [2c6617e2f9](https://linux-hardware.org/?probe=2c6617e2f9) | Jul 27, 2023 |
| Acer          | Extensa 215-32              | [18d32a6c36](https://linux-hardware.org/?probe=18d32a6c36) | Jul 27, 2023 |
| Compaq        | PRESARIOCQ18                | [c528c90b50](https://linux-hardware.org/?probe=c528c90b50) | Jul 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [6e7d094f7f](https://linux-hardware.org/?probe=6e7d094f7f) | Jul 27, 2023 |
| Dell          | Inspiron 5720               | [8674c464bd](https://linux-hardware.org/?probe=8674c464bd) | Jul 27, 2023 |
| Google        | Vortininja                  | [70f9ee30d3](https://linux-hardware.org/?probe=70f9ee30d3) | Jul 27, 2023 |
| Acer          | Aspire A315-23G             | [4d7b874be2](https://linux-hardware.org/?probe=4d7b874be2) | Jul 27, 2023 |
| Fujitsu       | LIFEBOOK U748               | [23d71a87d0](https://linux-hardware.org/?probe=23d71a87d0) | Jul 26, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [0552cb3e44](https://linux-hardware.org/?probe=0552cb3e44) | Jul 26, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [b2dd23136f](https://linux-hardware.org/?probe=b2dd23136f) | Jul 26, 2023 |
| Dell          | XPS 13 7390                 | [0217675942](https://linux-hardware.org/?probe=0217675942) | Jul 26, 2023 |
| Dell          | Precision 3520              | [2502fbaef2](https://linux-hardware.org/?probe=2502fbaef2) | Jul 26, 2023 |
| Acer          | Swift SF314-512             | [856e36fa9c](https://linux-hardware.org/?probe=856e36fa9c) | Jul 26, 2023 |
| Dell          | Vostro 3405                 | [82a990b785](https://linux-hardware.org/?probe=82a990b785) | Jul 26, 2023 |
| Dell          | Vostro 3405                 | [dc97ca175a](https://linux-hardware.org/?probe=dc97ca175a) | Jul 25, 2023 |
| HP            | ProBook 640 G2              | [ae244aab21](https://linux-hardware.org/?probe=ae244aab21) | Jul 25, 2023 |
| Apple         | MacBookPro5,5               | [9cf2abf318](https://linux-hardware.org/?probe=9cf2abf318) | Jul 25, 2023 |
| Google        | Droid                       | [ae803483c2](https://linux-hardware.org/?probe=ae803483c2) | Jul 25, 2023 |
| Dell          | XPS 13 9370                 | [835ca23b88](https://linux-hardware.org/?probe=835ca23b88) | Jul 25, 2023 |
| HP            | Laptop 15-db0xxx            | [f01ec95642](https://linux-hardware.org/?probe=f01ec95642) | Jul 25, 2023 |
| Dell          | XPS 13 9370                 | [321bdf6295](https://linux-hardware.org/?probe=321bdf6295) | Jul 25, 2023 |
| Acer          | Aspire 3610                 | [b40dd6ad17](https://linux-hardware.org/?probe=b40dd6ad17) | Jul 25, 2023 |
| MSI           | Katana GF66 11UG            | [bd45023e8e](https://linux-hardware.org/?probe=bd45023e8e) | Jul 25, 2023 |
| HP            | Laptop 15-fc0xxx            | [5c52eecd16](https://linux-hardware.org/?probe=5c52eecd16) | Jul 25, 2023 |
| SANTECH       | NHx0DB,DE                   | [80aa11a7e8](https://linux-hardware.org/?probe=80aa11a7e8) | Jul 25, 2023 |
| Dell          | Latitude 3420               | [18d920dab2](https://linux-hardware.org/?probe=18d920dab2) | Jul 24, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [fd441fa52f](https://linux-hardware.org/?probe=fd441fa52f) | Jul 24, 2023 |
| ASUSTek       | X541UV                      | [eb0aac9c32](https://linux-hardware.org/?probe=eb0aac9c32) | Jul 24, 2023 |
| Acer          | Nitro AN515-57              | [ae6caf81d7](https://linux-hardware.org/?probe=ae6caf81d7) | Jul 24, 2023 |
| Acer          | Aspire A515-45              | [e1de4fabc7](https://linux-hardware.org/?probe=e1de4fabc7) | Jul 24, 2023 |
| Timi          | A7S                         | [d0bcd36416](https://linux-hardware.org/?probe=d0bcd36416) | Jul 24, 2023 |
| Dell          | Inspiron 15 3511            | [980ed56abe](https://linux-hardware.org/?probe=980ed56abe) | Jul 24, 2023 |
| MSI           | Alpha 15 B5EEK              | [ea2f3666ba](https://linux-hardware.org/?probe=ea2f3666ba) | Jul 23, 2023 |
| Dell          | Latitude E7250              | [4b91b375d4](https://linux-hardware.org/?probe=4b91b375d4) | Jul 23, 2023 |
| Dell          | Latitude 7480               | [acad753aa8](https://linux-hardware.org/?probe=acad753aa8) | Jul 23, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | [a3350e1d80](https://linux-hardware.org/?probe=a3350e1d80) | Jul 23, 2023 |
| Acer          | Aspire A315-21              | [17f482e878](https://linux-hardware.org/?probe=17f482e878) | Jul 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d957d5efe0](https://linux-hardware.org/?probe=d957d5efe0) | Jul 22, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [467cc30f89](https://linux-hardware.org/?probe=467cc30f89) | Jul 22, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [bbd3181f1f](https://linux-hardware.org/?probe=bbd3181f1f) | Jul 22, 2023 |
| HP            | EliteBook 840 G1            | [cafa1082f8](https://linux-hardware.org/?probe=cafa1082f8) | Jul 22, 2023 |
| HP            | Presario CQ57               | [2c1bcfe898](https://linux-hardware.org/?probe=2c1bcfe898) | Jul 22, 2023 |
| Dell          | Inspiron 3558               | [2cad6d3cb7](https://linux-hardware.org/?probe=2cad6d3cb7) | Jul 22, 2023 |
| Dell          | Latitude 5580               | [06c9677557](https://linux-hardware.org/?probe=06c9677557) | Jul 22, 2023 |
| HP            | ENVY Laptop 17-ch2xxx       | [7d88a01e49](https://linux-hardware.org/?probe=7d88a01e49) | Jul 22, 2023 |
| HP            | 635                         | [bb148a8b2b](https://linux-hardware.org/?probe=bb148a8b2b) | Jul 21, 2023 |
| ASUSTek       | K72Jr                       | [cdb9b29f94](https://linux-hardware.org/?probe=cdb9b29f94) | Jul 21, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [031d46c9d0](https://linux-hardware.org/?probe=031d46c9d0) | Jul 21, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | [fc45e9b064](https://linux-hardware.org/?probe=fc45e9b064) | Jul 21, 2023 |
| Acer          | Swift SF314-512             | [d82c78621f](https://linux-hardware.org/?probe=d82c78621f) | Jul 20, 2023 |
| Lenovo        | ThinkPad T520 42435UG       | [820630ba9e](https://linux-hardware.org/?probe=820630ba9e) | Jul 20, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [7527ca0197](https://linux-hardware.org/?probe=7527ca0197) | Jul 20, 2023 |
| HP            | Pavilion Notebook           | [d366e7101c](https://linux-hardware.org/?probe=d366e7101c) | Jul 20, 2023 |
| ASUSTek       | T100TAM                     | [43cb18f0ee](https://linux-hardware.org/?probe=43cb18f0ee) | Jul 20, 2023 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [311144e138](https://linux-hardware.org/?probe=311144e138) | Jul 20, 2023 |
| Shanghai Z... | ZXE CRB                     | [da6bb4265c](https://linux-hardware.org/?probe=da6bb4265c) | Jul 20, 2023 |
| Notebook      | N650DU                      | [c04f4faa06](https://linux-hardware.org/?probe=c04f4faa06) | Jul 19, 2023 |
| Acer          | Swift SF314-43              | [6f00498896](https://linux-hardware.org/?probe=6f00498896) | Jul 19, 2023 |
| HP            | Pavilion 15                 | [e1bfe97e63](https://linux-hardware.org/?probe=e1bfe97e63) | Jul 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [524d69b498](https://linux-hardware.org/?probe=524d69b498) | Jul 19, 2023 |
| Acer          | Aspire 7739Z                | [3e75dec5e0](https://linux-hardware.org/?probe=3e75dec5e0) | Jul 19, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [9672a393c9](https://linux-hardware.org/?probe=9672a393c9) | Jul 19, 2023 |
| HP            | Pavilion 17                 | [bf76e4c333](https://linux-hardware.org/?probe=bf76e4c333) | Jul 19, 2023 |
| Acer          | Extensa 215-22              | [fc3dadd5bc](https://linux-hardware.org/?probe=fc3dadd5bc) | Jul 19, 2023 |
| Acer          | Nitro AN515-57              | [cdad3aa931](https://linux-hardware.org/?probe=cdad3aa931) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [bddb3e26c1](https://linux-hardware.org/?probe=bddb3e26c1) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [a4584a139f](https://linux-hardware.org/?probe=a4584a139f) | Jul 19, 2023 |
| HP            | EliteBook 8570p             | [8e456f1108](https://linux-hardware.org/?probe=8e456f1108) | Jul 18, 2023 |
| Lenovo        | ThinkPad T520 42435UG       | [f789cd31fa](https://linux-hardware.org/?probe=f789cd31fa) | Jul 18, 2023 |
| MSI           | GF63 Thin 11UC              | [3ef8cdcacb](https://linux-hardware.org/?probe=3ef8cdcacb) | Jul 18, 2023 |
| Dell          | Vostro 3500                 | [69cc1eb6f6](https://linux-hardware.org/?probe=69cc1eb6f6) | Jul 18, 2023 |
| Google        | Lillipup                    | [7f7ba76942](https://linux-hardware.org/?probe=7f7ba76942) | Jul 18, 2023 |
| HP            | Pavilion 15                 | [a5485bb7e0](https://linux-hardware.org/?probe=a5485bb7e0) | Jul 18, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [c6da4f3b1e](https://linux-hardware.org/?probe=c6da4f3b1e) | Jul 18, 2023 |
| Lenovo        | ThinkPad L580 20LW000WGE    | [1b210ca778](https://linux-hardware.org/?probe=1b210ca778) | Jul 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [35d510901b](https://linux-hardware.org/?probe=35d510901b) | Jul 18, 2023 |
| HP            | Laptop 17-cp0xxx            | [9d9ff78d29](https://linux-hardware.org/?probe=9d9ff78d29) | Jul 18, 2023 |
| Toshiba       | Satellite L755              | [da4d6e8a5c](https://linux-hardware.org/?probe=da4d6e8a5c) | Jul 18, 2023 |
| MSI           | GF63 Thin 11UC              | [f4fc84ba4b](https://linux-hardware.org/?probe=f4fc84ba4b) | Jul 17, 2023 |
| ASUSTek       | X505BA                      | [fcd96492f0](https://linux-hardware.org/?probe=fcd96492f0) | Jul 17, 2023 |
| Unknown       | TU-142                      | [d62ade82c2](https://linux-hardware.org/?probe=d62ade82c2) | Jul 17, 2023 |
| Dell          | Inspiron 16 7610            | [6d77ef17a0](https://linux-hardware.org/?probe=6d77ef17a0) | Jul 17, 2023 |
| HP            | Pavilion dm1                | [135bb20fbd](https://linux-hardware.org/?probe=135bb20fbd) | Jul 17, 2023 |
| Acer          | Aspire A515-57T             | [dd4a3bf595](https://linux-hardware.org/?probe=dd4a3bf595) | Jul 17, 2023 |
| Acer          | Aspire A315-23G             | [df26ae3dab](https://linux-hardware.org/?probe=df26ae3dab) | Jul 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [ab43e6b8ef](https://linux-hardware.org/?probe=ab43e6b8ef) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [6b52cef555](https://linux-hardware.org/?probe=6b52cef555) | Jul 16, 2023 |
| Dell          | Latitude E6440              | [c1de0cf4d1](https://linux-hardware.org/?probe=c1de0cf4d1) | Jul 16, 2023 |
| Dell          | Latitude E6320              | [0087a8e5cf](https://linux-hardware.org/?probe=0087a8e5cf) | Jul 16, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [65e4fb1356](https://linux-hardware.org/?probe=65e4fb1356) | Jul 16, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | [899c1452e4](https://linux-hardware.org/?probe=899c1452e4) | Jul 16, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | [497e6c5432](https://linux-hardware.org/?probe=497e6c5432) | Jul 16, 2023 |
| HP            | Laptop 14s-dq2xxx           | [cd9bfc68b6](https://linux-hardware.org/?probe=cd9bfc68b6) | Jul 16, 2023 |
| SIRAGON       | LM-C100                     | [daef084233](https://linux-hardware.org/?probe=daef084233) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [1625385cef](https://linux-hardware.org/?probe=1625385cef) | Jul 16, 2023 |
| Dell          | Latitude D610               | [791cabd713](https://linux-hardware.org/?probe=791cabd713) | Jul 16, 2023 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [02af27da78](https://linux-hardware.org/?probe=02af27da78) | Jul 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d43ad7594c](https://linux-hardware.org/?probe=d43ad7594c) | Jul 16, 2023 |
| Dell          | Latitude E6330              | [6adb67344f](https://linux-hardware.org/?probe=6adb67344f) | Jul 15, 2023 |
| Lenovo        | ThinkPad X260 20F5S04B00    | [8d3168b6c4](https://linux-hardware.org/?probe=8d3168b6c4) | Jul 15, 2023 |
| Acer          | Aspire R7-371T              | [c4f6270bdb](https://linux-hardware.org/?probe=c4f6270bdb) | Jul 15, 2023 |
| SLIMBOOK      | PROX15-AMD                  | [7e088e838b](https://linux-hardware.org/?probe=7e088e838b) | Jul 15, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1VD0... | [b62ed55325](https://linux-hardware.org/?probe=b62ed55325) | Jul 15, 2023 |
| Dell          | Latitude 7490               | [6811ebe45a](https://linux-hardware.org/?probe=6811ebe45a) | Jul 15, 2023 |
| Apple         | MacBookPro14,3              | [bd2e85e3ce](https://linux-hardware.org/?probe=bd2e85e3ce) | Jul 15, 2023 |
| HUAWEI        | KLVL-WXXW                   | [c76e3df311](https://linux-hardware.org/?probe=c76e3df311) | Jul 14, 2023 |
| Lenovo        | ThinkPad T530 2429HD6       | [1c48702f3c](https://linux-hardware.org/?probe=1c48702f3c) | Jul 14, 2023 |
| Coradir       | Coradir/ES10IS5             | [571080a9d5](https://linux-hardware.org/?probe=571080a9d5) | Jul 14, 2023 |
| Lenovo        | ThinkPad X220 4290FC1       | [d6c0ccb8f1](https://linux-hardware.org/?probe=d6c0ccb8f1) | Jul 14, 2023 |
| HP            | ProBook 640 G2              | [e5efd1b971](https://linux-hardware.org/?probe=e5efd1b971) | Jul 14, 2023 |
| HP            | EliteBook 840 G5            | [02b5ea8525](https://linux-hardware.org/?probe=02b5ea8525) | Jul 14, 2023 |
| HP            | Pavilion dm1                | [3b05c5dc5c](https://linux-hardware.org/?probe=3b05c5dc5c) | Jul 14, 2023 |
| Dell          | Inspiron 15 3511            | [e6d47a005f](https://linux-hardware.org/?probe=e6d47a005f) | Jul 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [e790a3c22f](https://linux-hardware.org/?probe=e790a3c22f) | Jul 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [dae11c33ed](https://linux-hardware.org/?probe=dae11c33ed) | Jul 14, 2023 |
| Google        | Blorb                       | [6bbcc9b8f3](https://linux-hardware.org/?probe=6bbcc9b8f3) | Jul 14, 2023 |
| Lenovo        | ThinkPad X260 20F5S04B00    | [ae8ecf10e7](https://linux-hardware.org/?probe=ae8ecf10e7) | Jul 13, 2023 |
| Lenovo        | V14-IIL 82C4                | [42aba63af0](https://linux-hardware.org/?probe=42aba63af0) | Jul 13, 2023 |
| HP            | 245 G8                      | [07eefc20b0](https://linux-hardware.org/?probe=07eefc20b0) | Jul 13, 2023 |
| Valve         | Jupiter                     | [14f7ea4a48](https://linux-hardware.org/?probe=14f7ea4a48) | Jul 13, 2023 |
| Dell          | XPS 17 9730                 | [b074a1deb3](https://linux-hardware.org/?probe=b074a1deb3) | Jul 13, 2023 |
| Google        | Reks                        | [680b857c0d](https://linux-hardware.org/?probe=680b857c0d) | Jul 13, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [7d2bb16563](https://linux-hardware.org/?probe=7d2bb16563) | Jul 13, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [b054249d03](https://linux-hardware.org/?probe=b054249d03) | Jul 13, 2023 |
| MSI           | Alpha 15 A4DEK              | [9a192c4a0b](https://linux-hardware.org/?probe=9a192c4a0b) | Jul 13, 2023 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [34ec75d601](https://linux-hardware.org/?probe=34ec75d601) | Jul 13, 2023 |
| Dell          | Latitude E6330              | [58ec0684cd](https://linux-hardware.org/?probe=58ec0684cd) | Jul 13, 2023 |
| MSI           | Stealth 16Studio A13VG      | [ab3683571a](https://linux-hardware.org/?probe=ab3683571a) | Jul 13, 2023 |
| Acer          | Aspire A515-52              | [56b110f152](https://linux-hardware.org/?probe=56b110f152) | Jul 13, 2023 |
| Acer          | Aspire A515-52              | [ad9fd505fa](https://linux-hardware.org/?probe=ad9fd505fa) | Jul 13, 2023 |
| Toshiba       | Satellite S75-B             | [ee71e28c8f](https://linux-hardware.org/?probe=ee71e28c8f) | Jul 12, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [603a591fcb](https://linux-hardware.org/?probe=603a591fcb) | Jul 12, 2023 |
| Google        | Lillipup                    | [b7b430e7b4](https://linux-hardware.org/?probe=b7b430e7b4) | Jul 12, 2023 |
| Positivo      | Mobile                      | [463636c0a2](https://linux-hardware.org/?probe=463636c0a2) | Jul 12, 2023 |
| Lenovo        | G570 4334                   | [27a207ead6](https://linux-hardware.org/?probe=27a207ead6) | Jul 12, 2023 |
| Acer          | Aspire 5820TG               | [86cfbf79ce](https://linux-hardware.org/?probe=86cfbf79ce) | Jul 12, 2023 |
| MSI           | FX603                       | [a2c598f9eb](https://linux-hardware.org/?probe=a2c598f9eb) | Jul 12, 2023 |
| MSI           | SUMMIT E13FlipEvo A12MT     | [90faae34f3](https://linux-hardware.org/?probe=90faae34f3) | Jul 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [15c5dec8dc](https://linux-hardware.org/?probe=15c5dec8dc) | Jul 12, 2023 |
| Dell          | XPS 13 9380                 | [e40c69408d](https://linux-hardware.org/?probe=e40c69408d) | Jul 11, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [9fc68063e3](https://linux-hardware.org/?probe=9fc68063e3) | Jul 11, 2023 |
| Dell          | Latitude 7275               | [0647894f7f](https://linux-hardware.org/?probe=0647894f7f) | Jul 11, 2023 |
| Fujitsu       | LIFEBOOK E780               | [ab432dcb0e](https://linux-hardware.org/?probe=ab432dcb0e) | Jul 11, 2023 |
| HP            | ProBook 4730s               | [0b6a6c7260](https://linux-hardware.org/?probe=0b6a6c7260) | Jul 11, 2023 |
| HP            | EliteBook 645 14 inch G9... | [65f4b4e813](https://linux-hardware.org/?probe=65f4b4e813) | Jul 11, 2023 |
| Unknown       | HP Chromebook 14            | [63b183aa51](https://linux-hardware.org/?probe=63b183aa51) | Jul 11, 2023 |
| HP            | EliteBook 1040 G4           | [d7209e7141](https://linux-hardware.org/?probe=d7209e7141) | Jul 11, 2023 |
| Dell          | Inspiron 7560               | [a761bfffd2](https://linux-hardware.org/?probe=a761bfffd2) | Jul 11, 2023 |
| HP            | ZBook 15 G6                 | [47ea5a35cb](https://linux-hardware.org/?probe=47ea5a35cb) | Jul 11, 2023 |
| HP            | EliteBook 1040 G4           | [33aa3fcdbc](https://linux-hardware.org/?probe=33aa3fcdbc) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | [fe9bfd5f77](https://linux-hardware.org/?probe=fe9bfd5f77) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | [d4dadd2e77](https://linux-hardware.org/?probe=d4dadd2e77) | Jul 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [707f0b8eeb](https://linux-hardware.org/?probe=707f0b8eeb) | Jul 10, 2023 |
| HP            | Victus by Laptop 16-e1xx... | [a14d8855bc](https://linux-hardware.org/?probe=a14d8855bc) | Jul 10, 2023 |
| Dell          | OptiPlex 9020               | [3384a64b67](https://linux-hardware.org/?probe=3384a64b67) | Jul 10, 2023 |
| Fujitsu       | LIFEBOOK U727               | [ce095d85c9](https://linux-hardware.org/?probe=ce095d85c9) | Jul 09, 2023 |
| HP            | Pro x2 612 G1 Tablet USA... | [c10c965a51](https://linux-hardware.org/?probe=c10c965a51) | Jul 09, 2023 |
| Acer          | Aspire V3-372T              | [566ff1d23e](https://linux-hardware.org/?probe=566ff1d23e) | Jul 09, 2023 |
| Toshiba       | PORTEGE Z30-C               | [f9d1d19d05](https://linux-hardware.org/?probe=f9d1d19d05) | Jul 09, 2023 |
| MSI           | Modern 14 B11MOU            | [c2e76ab704](https://linux-hardware.org/?probe=c2e76ab704) | Jul 09, 2023 |
| ASUSTek       | VivoBook S14 X430UA         | [fdb15c83de](https://linux-hardware.org/?probe=fdb15c83de) | Jul 09, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [59f06e2baf](https://linux-hardware.org/?probe=59f06e2baf) | Jul 09, 2023 |
| Acer          | Aspire F5-573G              | [10cf2c3aa5](https://linux-hardware.org/?probe=10cf2c3aa5) | Jul 09, 2023 |
| Acer          | Aspire V3-372T              | [f2a9fbdf50](https://linux-hardware.org/?probe=f2a9fbdf50) | Jul 09, 2023 |
| HP            | EliteBook 8560p             | [39fe220963](https://linux-hardware.org/?probe=39fe220963) | Jul 09, 2023 |
| Dell          | Inspiron N4050              | [d5fa70cfda](https://linux-hardware.org/?probe=d5fa70cfda) | Jul 08, 2023 |
| Acer          | TravelMate P215-53          | [5810f4f1f8](https://linux-hardware.org/?probe=5810f4f1f8) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | [6a739102d0](https://linux-hardware.org/?probe=6a739102d0) | Jul 08, 2023 |
| Dell          | Vostro 15 3535              | [8b67e5b282](https://linux-hardware.org/?probe=8b67e5b282) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [ae008e5343](https://linux-hardware.org/?probe=ae008e5343) | Jul 07, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | [96d1578908](https://linux-hardware.org/?probe=96d1578908) | Jul 07, 2023 |
| HP            | EliteBook 1040 G4           | [cbc100e6b1](https://linux-hardware.org/?probe=cbc100e6b1) | Jul 07, 2023 |
| HP            | EliteBook 1040 G4           | [3177785c7f](https://linux-hardware.org/?probe=3177785c7f) | Jul 07, 2023 |
| HP            | ProBook 430 G1              | [abb4e75faa](https://linux-hardware.org/?probe=abb4e75faa) | Jul 07, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [5d03b4b2ad](https://linux-hardware.org/?probe=5d03b4b2ad) | Jul 07, 2023 |
| Lenovo        | ThinkPad T450s 20BWS0PJ0... | [2345d00757](https://linux-hardware.org/?probe=2345d00757) | Jul 07, 2023 |
| Lenovo        | Flex 2-14 20404             | [93f50211c2](https://linux-hardware.org/?probe=93f50211c2) | Jul 07, 2023 |
| HUAWEI        | BOM-WXX9                    | [905af6686d](https://linux-hardware.org/?probe=905af6686d) | Jul 06, 2023 |
| Dell          | Latitude 7430               | [743d41d534](https://linux-hardware.org/?probe=743d41d534) | Jul 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [37f1a0082b](https://linux-hardware.org/?probe=37f1a0082b) | Jul 06, 2023 |
| Lenovo        | ThinkPad T470 20HES05500    | [12b31081e2](https://linux-hardware.org/?probe=12b31081e2) | Jul 06, 2023 |
| HONOR         | BOHK-WAX9X                  | [95d2ae1051](https://linux-hardware.org/?probe=95d2ae1051) | Jul 06, 2023 |
| HONOR         | BOHK-WAX9X                  | [4f6d2375a3](https://linux-hardware.org/?probe=4f6d2375a3) | Jul 06, 2023 |
| Apple         | MacBookAir7,2               | [c1d387dfc5](https://linux-hardware.org/?probe=c1d387dfc5) | Jul 06, 2023 |
| Dell          | XPS 15 9520                 | [f255433162](https://linux-hardware.org/?probe=f255433162) | Jul 06, 2023 |
| Dell          | Precision M6800             | [4b8d02d04a](https://linux-hardware.org/?probe=4b8d02d04a) | Jul 06, 2023 |
| Dell          | Precision M6800             | [239c3ea2b9](https://linux-hardware.org/?probe=239c3ea2b9) | Jul 06, 2023 |
| Apple         | MacBookPro14,3              | [d6153317bf](https://linux-hardware.org/?probe=d6153317bf) | Jul 05, 2023 |
| Samsung       | 770Z5E/780Z5E               | [2d38e98c83](https://linux-hardware.org/?probe=2d38e98c83) | Jul 05, 2023 |
| Apple         | MacBook5,2                  | [41366bcd54](https://linux-hardware.org/?probe=41366bcd54) | Jul 05, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9d57d6a85f](https://linux-hardware.org/?probe=9d57d6a85f) | Jul 05, 2023 |
| Dell          | Inspiron 15-3565            | [69d01e9a98](https://linux-hardware.org/?probe=69d01e9a98) | Jul 05, 2023 |
| HP            | ProBook 450 G5              | [7a15493631](https://linux-hardware.org/?probe=7a15493631) | Jul 05, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [fc1c7254b3](https://linux-hardware.org/?probe=fc1c7254b3) | Jul 04, 2023 |
| NEC Comput... | PC-VK27MBZCG                | [5db0d02025](https://linux-hardware.org/?probe=5db0d02025) | Jul 04, 2023 |
| MSI           | Creator 15M A9SD            | [84c85a8969](https://linux-hardware.org/?probe=84c85a8969) | Jul 04, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [79c5344e62](https://linux-hardware.org/?probe=79c5344e62) | Jul 04, 2023 |
| Google        | Lick                        | [f2b9397a8b](https://linux-hardware.org/?probe=f2b9397a8b) | Jul 04, 2023 |
| ASUSTek       | G750JX                      | [10f49d74ef](https://linux-hardware.org/?probe=10f49d74ef) | Jul 04, 2023 |
| HP            | EliteBook 6930p             | [b7328dc212](https://linux-hardware.org/?probe=b7328dc212) | Jul 04, 2023 |
| Acer          | Aspire 6930                 | [772d3d7f4a](https://linux-hardware.org/?probe=772d3d7f4a) | Jul 04, 2023 |
| HP            | Pavilion dv6                | [517e6b81c1](https://linux-hardware.org/?probe=517e6b81c1) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [73146ccba2](https://linux-hardware.org/?probe=73146ccba2) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [19a254cdee](https://linux-hardware.org/?probe=19a254cdee) | Jul 03, 2023 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | [18230f7c64](https://linux-hardware.org/?probe=18230f7c64) | Jul 03, 2023 |
| HP            | EliteBook 840 G3            | [ed37dd6278](https://linux-hardware.org/?probe=ed37dd6278) | Jul 03, 2023 |
| Fujitsu       | LIFEBOOK E780               | [2eb6c4356c](https://linux-hardware.org/?probe=2eb6c4356c) | Jul 02, 2023 |
| HONOR         | NMH-WCX9                    | [a8caf9af8e](https://linux-hardware.org/?probe=a8caf9af8e) | Jul 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | [4055aa6f2b](https://linux-hardware.org/?probe=4055aa6f2b) | Jul 02, 2023 |
| Dell          | Latitude 3410               | [11d9814008](https://linux-hardware.org/?probe=11d9814008) | Jul 02, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [4708f2b480](https://linux-hardware.org/?probe=4708f2b480) | Jul 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [54987b03a1](https://linux-hardware.org/?probe=54987b03a1) | Jul 02, 2023 |
| HP            | Laptop 15-dw3xxx            | [3fe182f682](https://linux-hardware.org/?probe=3fe182f682) | Jul 02, 2023 |
| HP            | Pavilion dv7                | [e10b64716f](https://linux-hardware.org/?probe=e10b64716f) | Jul 01, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [b98b20a82c](https://linux-hardware.org/?probe=b98b20a82c) | Jul 01, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [1cc2f89c1a](https://linux-hardware.org/?probe=1cc2f89c1a) | Jul 01, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [6484578658](https://linux-hardware.org/?probe=6484578658) | Jul 01, 2023 |
| HP            | EliteBook 2570p             | [c55a78c98a](https://linux-hardware.org/?probe=c55a78c98a) | Jul 01, 2023 |
| ASUSTek       | X541UV                      | [d0fc2ea58e](https://linux-hardware.org/?probe=d0fc2ea58e) | Jul 01, 2023 |
| Dell          | Inspiron 7720               | [9d8f40247e](https://linux-hardware.org/?probe=9d8f40247e) | Jul 01, 2023 |
| ASUSTek       | X541UV                      | [8b5dc3456b](https://linux-hardware.org/?probe=8b5dc3456b) | Jul 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [0aed51f639](https://linux-hardware.org/?probe=0aed51f639) | Jul 01, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [55bfc9f544](https://linux-hardware.org/?probe=55bfc9f544) | Jul 01, 2023 |
| Apple         | MacBookPro14,3              | [4a51b35cb8](https://linux-hardware.org/?probe=4a51b35cb8) | Jul 01, 2023 |
| Dell          | Latitude 3500               | [8e82f9abda](https://linux-hardware.org/?probe=8e82f9abda) | Jul 01, 2023 |
| HUAWEI        | BOM-WXX9                    | [4d4d992cb0](https://linux-hardware.org/?probe=4d4d992cb0) | Jul 01, 2023 |
| HP            | 255 G8 Notebook PC          | [3c3ddffa8b](https://linux-hardware.org/?probe=3c3ddffa8b) | Jul 01, 2023 |
| Acer          | Aspire V5-123               | [8507833f22](https://linux-hardware.org/?probe=8507833f22) | Jul 01, 2023 |
| ASUSTek       | K501UX                      | [a7fb172b7d](https://linux-hardware.org/?probe=a7fb172b7d) | Jun 30, 2023 |
| Apple         | MacBookAir7,2               | [cb1bcce659](https://linux-hardware.org/?probe=cb1bcce659) | Jun 30, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [39a8ee4269](https://linux-hardware.org/?probe=39a8ee4269) | Jun 30, 2023 |
| HP            | EliteBook 850 G1            | [a5f3a5ad14](https://linux-hardware.org/?probe=a5f3a5ad14) | Jun 30, 2023 |
| Lenovo        | ThinkPad T495 20NK000XBR    | [2b5e40efaa](https://linux-hardware.org/?probe=2b5e40efaa) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430s 23554L7      | [501b0860c8](https://linux-hardware.org/?probe=501b0860c8) | Jun 30, 2023 |
| Dell          | G3 3590                     | [5c7312fed9](https://linux-hardware.org/?probe=5c7312fed9) | Jun 30, 2023 |
| Lenovo        | ThinkPad L512 44444NG       | [300a79aa88](https://linux-hardware.org/?probe=300a79aa88) | Jun 30, 2023 |
| ASUSTek       | T100TA                      | [921821fda8](https://linux-hardware.org/?probe=921821fda8) | Jun 30, 2023 |
| ASUSTek       | K52F                        | [98e9b448c7](https://linux-hardware.org/?probe=98e9b448c7) | Jun 30, 2023 |
| Acer          | Aspire V3-772               | [0fae87e118](https://linux-hardware.org/?probe=0fae87e118) | Jun 29, 2023 |
| Acer          | TravelMate P449-G2-M        | [b9291d6951](https://linux-hardware.org/?probe=b9291d6951) | Jun 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | [62ff10cadc](https://linux-hardware.org/?probe=62ff10cadc) | Jun 29, 2023 |
| Lenovo        | ThinkPad T440p 2000CT0      | [10c852dc38](https://linux-hardware.org/?probe=10c852dc38) | Jun 29, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [25a1aaf938](https://linux-hardware.org/?probe=25a1aaf938) | Jun 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | [a50310948a](https://linux-hardware.org/?probe=a50310948a) | Jun 29, 2023 |
| HP            | Pavilion dv6                | [b6c2bcb025](https://linux-hardware.org/?probe=b6c2bcb025) | Jun 29, 2023 |
| Dell          | Latitude 3500               | [e1831984f8](https://linux-hardware.org/?probe=e1831984f8) | Jun 28, 2023 |
| Dell          | Latitude 7370               | [cb11921012](https://linux-hardware.org/?probe=cb11921012) | Jun 28, 2023 |
| Aquarius      | NS585                       | [52a07593c9](https://linux-hardware.org/?probe=52a07593c9) | Jun 28, 2023 |
| HP            | Pavilion dv6                | [7fe9e439c0](https://linux-hardware.org/?probe=7fe9e439c0) | Jun 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [4a4411b820](https://linux-hardware.org/?probe=4a4411b820) | Jun 28, 2023 |
| Aquarius      | NS585                       | [b2f86e98f9](https://linux-hardware.org/?probe=b2f86e98f9) | Jun 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [2ed2f000d3](https://linux-hardware.org/?probe=2ed2f000d3) | Jun 28, 2023 |
| ASUSTek       | ZenBook Pro 15 UX550GEX_... | [56eef68e89](https://linux-hardware.org/?probe=56eef68e89) | Jun 28, 2023 |
| Acer          | Aspire A315-23G             | [1c07c9f0b8](https://linux-hardware.org/?probe=1c07c9f0b8) | Jun 28, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [ab4772fd2e](https://linux-hardware.org/?probe=ab4772fd2e) | Jun 28, 2023 |
| Lenovo        | ThinkPad X280 20KF001RUK    | [a1da72b9a5](https://linux-hardware.org/?probe=a1da72b9a5) | Jun 27, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [8112f38f33](https://linux-hardware.org/?probe=8112f38f33) | Jun 27, 2023 |
| Coradir       | Coradir/ES10IS5             | [d2d1f5b2a5](https://linux-hardware.org/?probe=d2d1f5b2a5) | Jun 27, 2023 |
| HP            | Laptop 15-ef1xxx            | [765d0708eb](https://linux-hardware.org/?probe=765d0708eb) | Jun 26, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | [5a062be874](https://linux-hardware.org/?probe=5a062be874) | Jun 26, 2023 |
| ASUSTek       | K53SJ                       | [fe211e4239](https://linux-hardware.org/?probe=fe211e4239) | Jun 26, 2023 |
| HP            | EliteBook 835 13 inch G1... | [e43818af40](https://linux-hardware.org/?probe=e43818af40) | Jun 26, 2023 |
| LG Electro... | 17Z90R-G.AD79F              | [0d641b84fe](https://linux-hardware.org/?probe=0d641b84fe) | Jun 26, 2023 |
| Acer          | Aspire A515-56              | [0ee45fd3e8](https://linux-hardware.org/?probe=0ee45fd3e8) | Jun 26, 2023 |
| Coradir       | Coradir/ES10IS5             | [d6a1e61945](https://linux-hardware.org/?probe=d6a1e61945) | Jun 26, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [b8a3042b9d](https://linux-hardware.org/?probe=b8a3042b9d) | Jun 26, 2023 |
| Aquarius      | NS585                       | [25af22ec30](https://linux-hardware.org/?probe=25af22ec30) | Jun 26, 2023 |
| Aquarius      | NS585                       | [8e957a70f0](https://linux-hardware.org/?probe=8e957a70f0) | Jun 26, 2023 |
| Aquarius      | NS585                       | [bb09ae1f8d](https://linux-hardware.org/?probe=bb09ae1f8d) | Jun 26, 2023 |
| HP            | OMEN by Laptop              | [07d9cc6d71](https://linux-hardware.org/?probe=07d9cc6d71) | Jun 26, 2023 |
| Apple         | MacBook2,1                  | [f5c0a2fd49](https://linux-hardware.org/?probe=f5c0a2fd49) | Jun 26, 2023 |
| HP            | Compaq Mini 110c-1100       | [0dc147bd7c](https://linux-hardware.org/?probe=0dc147bd7c) | Jun 26, 2023 |
| Lenovo        | ThinkPad T430 34766TT       | [06ad7b4a25](https://linux-hardware.org/?probe=06ad7b4a25) | Jun 26, 2023 |
| Dell          | XPS 15 7590                 | [dfc817892b](https://linux-hardware.org/?probe=dfc817892b) | Jun 26, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [ed89cd0d05](https://linux-hardware.org/?probe=ed89cd0d05) | Jun 26, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [62665eec25](https://linux-hardware.org/?probe=62665eec25) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0a233c34b3](https://linux-hardware.org/?probe=0a233c34b3) | Jun 26, 2023 |
| Dell          | XPS 15 9530                 | [9c925666a5](https://linux-hardware.org/?probe=9c925666a5) | Jun 26, 2023 |
| Dell          | XPS 15 9530                 | [ea814b3f7b](https://linux-hardware.org/?probe=ea814b3f7b) | Jun 26, 2023 |
| Avell High... | A70 HYB                     | [3ccdaf3c82](https://linux-hardware.org/?probe=3ccdaf3c82) | Jun 26, 2023 |
| ASUSTek       | E403SA                      | [bdc47269c3](https://linux-hardware.org/?probe=bdc47269c3) | Jun 25, 2023 |
| HP            | Laptop 14-dq0xxx            | [695dd94347](https://linux-hardware.org/?probe=695dd94347) | Jun 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [cee2bb11dc](https://linux-hardware.org/?probe=cee2bb11dc) | Jun 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | [14cc9e067f](https://linux-hardware.org/?probe=14cc9e067f) | Jun 25, 2023 |
| Dell          | Inspiron 5593               | [06f1256f88](https://linux-hardware.org/?probe=06f1256f88) | Jun 25, 2023 |
| Dell          | Latitude E6430              | [be9b6c75da](https://linux-hardware.org/?probe=be9b6c75da) | Jun 25, 2023 |
| Toshiba       | IS 1413G                    | [a87db20468](https://linux-hardware.org/?probe=a87db20468) | Jun 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [a7df01b153](https://linux-hardware.org/?probe=a7df01b153) | Jun 24, 2023 |
| Dell          | Inspiron 1720               | [60c2ef3b92](https://linux-hardware.org/?probe=60c2ef3b92) | Jun 24, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [fe084d5ddb](https://linux-hardware.org/?probe=fe084d5ddb) | Jun 24, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | [a8420bc87d](https://linux-hardware.org/?probe=a8420bc87d) | Jun 24, 2023 |
| Acer          | Aspire VN7-591G             | [356b066ca9](https://linux-hardware.org/?probe=356b066ca9) | Jun 24, 2023 |
| Google        | Kip                         | [4e1bfd359e](https://linux-hardware.org/?probe=4e1bfd359e) | Jun 24, 2023 |
| HP            | EliteBook 830 G5            | [2b61a56610](https://linux-hardware.org/?probe=2b61a56610) | Jun 24, 2023 |
| Dell          | XPS 15 9570                 | [2c09eb930c](https://linux-hardware.org/?probe=2c09eb930c) | Jun 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [3cc7c77a76](https://linux-hardware.org/?probe=3cc7c77a76) | Jun 23, 2023 |
| HP            | 8470p EliteBook             | [da3719515b](https://linux-hardware.org/?probe=da3719515b) | Jun 23, 2023 |
| Acer          | Predator PH315-54           | [46d748a0a1](https://linux-hardware.org/?probe=46d748a0a1) | Jun 23, 2023 |
| Lenovo        | Edge 15 80H1                | [aff25effc2](https://linux-hardware.org/?probe=aff25effc2) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | [6d8c00ff02](https://linux-hardware.org/?probe=6d8c00ff02) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | [1c1a2724f4](https://linux-hardware.org/?probe=1c1a2724f4) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [3cdf59359c](https://linux-hardware.org/?probe=3cdf59359c) | Jun 23, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [5298e132fc](https://linux-hardware.org/?probe=5298e132fc) | Jun 23, 2023 |
| Acer          | Aspire A515-55              | [bf6de06fb9](https://linux-hardware.org/?probe=bf6de06fb9) | Jun 23, 2023 |
| VIT           | P2423                       | [19242b2ddb](https://linux-hardware.org/?probe=19242b2ddb) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | [b5576af3f8](https://linux-hardware.org/?probe=b5576af3f8) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | [911336b572](https://linux-hardware.org/?probe=911336b572) | Jun 23, 2023 |
| Lenovo        | ThinkPad X230 2325SRQ       | [fd42553eea](https://linux-hardware.org/?probe=fd42553eea) | Jun 22, 2023 |
| ASUSTek       | X45U                        | [63a491a160](https://linux-hardware.org/?probe=63a491a160) | Jun 22, 2023 |
| Dell          | Inspiron 1525               | [1cdf3502e8](https://linux-hardware.org/?probe=1cdf3502e8) | Jun 21, 2023 |
| Dell          | Inspiron 1525               | [7bbc89ec0f](https://linux-hardware.org/?probe=7bbc89ec0f) | Jun 21, 2023 |
| Dell          | Latitude E5550              | [72f4d53246](https://linux-hardware.org/?probe=72f4d53246) | Jun 21, 2023 |
| Apple         | MacBookPro10,1              | [9841bf505c](https://linux-hardware.org/?probe=9841bf505c) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | [9f3829c99f](https://linux-hardware.org/?probe=9f3829c99f) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | [379e3473e2](https://linux-hardware.org/?probe=379e3473e2) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | [8a2a9fd293](https://linux-hardware.org/?probe=8a2a9fd293) | Jun 21, 2023 |
| Dell          | Inspiron 5570               | [d661316023](https://linux-hardware.org/?probe=d661316023) | Jun 21, 2023 |
| Lenovo        | IdeaPadFlex 15 20309        | [76fbd356a0](https://linux-hardware.org/?probe=76fbd356a0) | Jun 21, 2023 |
| Dell          | Latitude E5550              | [e1fdcf84b3](https://linux-hardware.org/?probe=e1fdcf84b3) | Jun 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [8a61f834dd](https://linux-hardware.org/?probe=8a61f834dd) | Jun 21, 2023 |
| Dell          | Vostro 5490                 | [10d1aeda8b](https://linux-hardware.org/?probe=10d1aeda8b) | Jun 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [291796e3e4](https://linux-hardware.org/?probe=291796e3e4) | Jun 21, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [dc5a63aacc](https://linux-hardware.org/?probe=dc5a63aacc) | Jun 20, 2023 |
| Apple         | MacBook6,1                  | [c7e1912b55](https://linux-hardware.org/?probe=c7e1912b55) | Jun 20, 2023 |
| Apple         | MacBook5,2                  | [53f708517b](https://linux-hardware.org/?probe=53f708517b) | Jun 20, 2023 |
| Google        | Stout                       | [cb67ad655e](https://linux-hardware.org/?probe=cb67ad655e) | Jun 20, 2023 |
| Packard Be... | EasyNote TE11HC             | [6bbc56b36c](https://linux-hardware.org/?probe=6bbc56b36c) | Jun 20, 2023 |
| Dell          | Latitude E7450              | [4760bb7306](https://linux-hardware.org/?probe=4760bb7306) | Jun 20, 2023 |
| Apple         | MacBookPro5,5               | [16c4045c3b](https://linux-hardware.org/?probe=16c4045c3b) | Jun 20, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [c3f77cf346](https://linux-hardware.org/?probe=c3f77cf346) | Jun 20, 2023 |
| Acer          | TravelMate P449-G2-M        | [98626bde6c](https://linux-hardware.org/?probe=98626bde6c) | Jun 20, 2023 |
| Dell          | Latitude 3410               | [1e0348842a](https://linux-hardware.org/?probe=1e0348842a) | Jun 19, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [a0862de551](https://linux-hardware.org/?probe=a0862de551) | Jun 19, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [3cfd8a448c](https://linux-hardware.org/?probe=3cfd8a448c) | Jun 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [42fd301e8b](https://linux-hardware.org/?probe=42fd301e8b) | Jun 19, 2023 |
| Lenovo        | IdeaPad S340-15APITouch ... | [fe617b45f8](https://linux-hardware.org/?probe=fe617b45f8) | Jun 19, 2023 |
| Toshiba       | TECRA R850                  | [c40116d0de](https://linux-hardware.org/?probe=c40116d0de) | Jun 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d8d9101ef6](https://linux-hardware.org/?probe=d8d9101ef6) | Jun 19, 2023 |
| Packard Be... | EasyNote TE11HC             | [33785e2493](https://linux-hardware.org/?probe=33785e2493) | Jun 18, 2023 |
| Dell          | Latitude E7450              | [addda016c8](https://linux-hardware.org/?probe=addda016c8) | Jun 18, 2023 |
| HP            | EliteBook 2530p             | [7d246caf6f](https://linux-hardware.org/?probe=7d246caf6f) | Jun 18, 2023 |
| HP            | EliteBook 8440p             | [4b1b2457a4](https://linux-hardware.org/?probe=4b1b2457a4) | Jun 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [e4c418382a](https://linux-hardware.org/?probe=e4c418382a) | Jun 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [26b4c05332](https://linux-hardware.org/?probe=26b4c05332) | Jun 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S10T0... | [a3dd392c51](https://linux-hardware.org/?probe=a3dd392c51) | Jun 17, 2023 |
| Dell          | Latitude E6400              | [0f8aca3e72](https://linux-hardware.org/?probe=0f8aca3e72) | Jun 17, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [d9e1222bc3](https://linux-hardware.org/?probe=d9e1222bc3) | Jun 17, 2023 |
| Dell          | Precision M2800             | [e9f259595a](https://linux-hardware.org/?probe=e9f259595a) | Jun 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [9cdeeb06de](https://linux-hardware.org/?probe=9cdeeb06de) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | [19e270cab0](https://linux-hardware.org/?probe=19e270cab0) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | [e4b27c6a92](https://linux-hardware.org/?probe=e4b27c6a92) | Jun 16, 2023 |
| Lenovo        | ThinkPad P51 20HJS1SF00     | [664ae7a0f2](https://linux-hardware.org/?probe=664ae7a0f2) | Jun 16, 2023 |
| Dell          | Latitude D620               | [8dc25931d7](https://linux-hardware.org/?probe=8dc25931d7) | Jun 16, 2023 |
| Dell          | Latitude D620               | [819f346812](https://linux-hardware.org/?probe=819f346812) | Jun 16, 2023 |
| HONOR         | NMH-WCX9                    | [ec1b8c4ef4](https://linux-hardware.org/?probe=ec1b8c4ef4) | Jun 16, 2023 |
| Dell          | Latitude E6400              | [7c59595887](https://linux-hardware.org/?probe=7c59595887) | Jun 16, 2023 |
| HUAWEI        | NBD-WXX9                    | [b9bf7ea3c2](https://linux-hardware.org/?probe=b9bf7ea3c2) | Jun 16, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [b05e4ee752](https://linux-hardware.org/?probe=b05e4ee752) | Jun 15, 2023 |
| HP            | Laptop 14-cm0xxx            | [67ed3346c2](https://linux-hardware.org/?probe=67ed3346c2) | Jun 15, 2023 |
| Unknown       | Unknown                     | [f1294224ee](https://linux-hardware.org/?probe=f1294224ee) | Jun 15, 2023 |
| HP            | Laptop 14-cm0xxx            | [07f1089ee7](https://linux-hardware.org/?probe=07f1089ee7) | Jun 15, 2023 |
| HUAWEI        | NBD-WXX9                    | [b55662cc58](https://linux-hardware.org/?probe=b55662cc58) | Jun 15, 2023 |
| Unknown       | Unknown                     | [9b8a05d0f9](https://linux-hardware.org/?probe=9b8a05d0f9) | Jun 15, 2023 |
| Acer          | TravelMate 8172             | [569fde2487](https://linux-hardware.org/?probe=569fde2487) | Jun 15, 2023 |
| Apple         | MacBookAir7,2               | [2db615249d](https://linux-hardware.org/?probe=2db615249d) | Jun 15, 2023 |
| Apple         | MacBookAir7,2               | [138e2807af](https://linux-hardware.org/?probe=138e2807af) | Jun 15, 2023 |
| Apple         | MacBookAir7,1               | [5d8061c350](https://linux-hardware.org/?probe=5d8061c350) | Jun 15, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [aafa9250df](https://linux-hardware.org/?probe=aafa9250df) | Jun 15, 2023 |
| Medion        | E6214                       | [71b2e69534](https://linux-hardware.org/?probe=71b2e69534) | Jun 15, 2023 |
| Lenovo        | B590 20206                  | [f7e4f16796](https://linux-hardware.org/?probe=f7e4f16796) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [eb0ba3c881](https://linux-hardware.org/?probe=eb0ba3c881) | Jun 15, 2023 |
| Toshiba       | Satellite L45-B             | [4cc6199522](https://linux-hardware.org/?probe=4cc6199522) | Jun 15, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [65298dde46](https://linux-hardware.org/?probe=65298dde46) | Jun 14, 2023 |
| HONOR         | BBR-WAX9                    | [b980e4f162](https://linux-hardware.org/?probe=b980e4f162) | Jun 14, 2023 |
| Dell          | Latitude 5480               | [677cb87f98](https://linux-hardware.org/?probe=677cb87f98) | Jun 14, 2023 |
| Dell          | XPS M1530                   | [252d777fa0](https://linux-hardware.org/?probe=252d777fa0) | Jun 14, 2023 |
| Acer          | TravelMate 5742Z            | [abf5dbde31](https://linux-hardware.org/?probe=abf5dbde31) | Jun 14, 2023 |
| Apple         | MacBookPro5,5               | [b639a64b45](https://linux-hardware.org/?probe=b639a64b45) | Jun 14, 2023 |
| Dell          | Latitude 7480               | [375fb09bca](https://linux-hardware.org/?probe=375fb09bca) | Jun 14, 2023 |
| Acer          | Aspire A315-23G             | [18a5adccb6](https://linux-hardware.org/?probe=18a5adccb6) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [e073b99b63](https://linux-hardware.org/?probe=e073b99b63) | Jun 13, 2023 |
| HP            | Pavilion Notebook           | [f444f44a49](https://linux-hardware.org/?probe=f444f44a49) | Jun 13, 2023 |
| Samsung       | 750XED                      | [8997330d6a](https://linux-hardware.org/?probe=8997330d6a) | Jun 13, 2023 |
| Fujitsu       | LIFEBOOK E780               | [b8631b65c4](https://linux-hardware.org/?probe=b8631b65c4) | Jun 13, 2023 |
| HP            | Pavilion dv7                | [3c113d457b](https://linux-hardware.org/?probe=3c113d457b) | Jun 13, 2023 |
| Sony          | SVE11116FGW                 | [4c34707bef](https://linux-hardware.org/?probe=4c34707bef) | Jun 13, 2023 |
| Sony          | SVE11116FGW                 | [a048cbcdeb](https://linux-hardware.org/?probe=a048cbcdeb) | Jun 13, 2023 |
| Acer          | TravelMate P449-G2-M        | [97b6ba8bd6](https://linux-hardware.org/?probe=97b6ba8bd6) | Jun 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [f578df0eb9](https://linux-hardware.org/?probe=f578df0eb9) | Jun 13, 2023 |
| Dell          | Inspiron 1521               | [b4a1eae7be](https://linux-hardware.org/?probe=b4a1eae7be) | Jun 12, 2023 |
| Apple         | MacBookPro12,1              | [a515b0dbf7](https://linux-hardware.org/?probe=a515b0dbf7) | Jun 12, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | [20b91b813f](https://linux-hardware.org/?probe=20b91b813f) | Jun 12, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [675f082570](https://linux-hardware.org/?probe=675f082570) | Jun 12, 2023 |
| HP            | EliteBook 840 G5            | [331ac1da01](https://linux-hardware.org/?probe=331ac1da01) | Jun 12, 2023 |
| Hampoo        | Cherry Trail CR V200        | [d2ee0bc234](https://linux-hardware.org/?probe=d2ee0bc234) | Jun 12, 2023 |
| HP            | EliteBook 2530p             | [8e5a09ba99](https://linux-hardware.org/?probe=8e5a09ba99) | Jun 12, 2023 |
| Fujitsu       | LIFEBOOK A514               | [45b16c1cdf](https://linux-hardware.org/?probe=45b16c1cdf) | Jun 12, 2023 |
| Fujitsu       | LIFEBOOK A514               | [1da963b3f4](https://linux-hardware.org/?probe=1da963b3f4) | Jun 12, 2023 |
| Dell          | Latitude 3320               | [e467a71dac](https://linux-hardware.org/?probe=e467a71dac) | Jun 12, 2023 |
| Dell          | Latitude 3320               | [ec4f04b63e](https://linux-hardware.org/?probe=ec4f04b63e) | Jun 12, 2023 |
| MSI           | GE62 6QC                    | [5581a5c589](https://linux-hardware.org/?probe=5581a5c589) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | [7a4183e095](https://linux-hardware.org/?probe=7a4183e095) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | [2051db7014](https://linux-hardware.org/?probe=2051db7014) | Jun 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [9ed0a99c90](https://linux-hardware.org/?probe=9ed0a99c90) | Jun 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [5bc42066ca](https://linux-hardware.org/?probe=5bc42066ca) | Jun 12, 2023 |
| Dell          | Inspiron 5515               | [9ac2f1ed7e](https://linux-hardware.org/?probe=9ac2f1ed7e) | Jun 12, 2023 |
| Dell          | Inspiron 3501               | [8e9562dd9a](https://linux-hardware.org/?probe=8e9562dd9a) | Jun 11, 2023 |
| Lenovo        | ThinkPad T420s 4175A16      | [3d23465019](https://linux-hardware.org/?probe=3d23465019) | Jun 11, 2023 |
| Lenovo        | G565 4385                   | [2fd61f3fc5](https://linux-hardware.org/?probe=2fd61f3fc5) | Jun 11, 2023 |
| MSI           | Prestige 15 A10SC           | [ceb7680734](https://linux-hardware.org/?probe=ceb7680734) | Jun 11, 2023 |
| ASUSTek       | ZenBook UX334FAC_UX334FA    | [ba762c6d80](https://linux-hardware.org/?probe=ba762c6d80) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [8b88702b69](https://linux-hardware.org/?probe=8b88702b69) | Jun 11, 2023 |
| Dell          | Latitude 7440               | [f63ada6c61](https://linux-hardware.org/?probe=f63ada6c61) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | [a62438daef](https://linux-hardware.org/?probe=a62438daef) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | [fab548c31e](https://linux-hardware.org/?probe=fab548c31e) | Jun 10, 2023 |
| IT Channel... | N8xEJEK                     | [51a7e3f5b4](https://linux-hardware.org/?probe=51a7e3f5b4) | Jun 10, 2023 |
| Acidanther... | MacBookPro15,2              | [fb30b2eb35](https://linux-hardware.org/?probe=fb30b2eb35) | Jun 10, 2023 |
| Intel         | powered classmate PC        | [e530f037c6](https://linux-hardware.org/?probe=e530f037c6) | Jun 09, 2023 |
| Dell          | Latitude 5480               | [5b3fb0b4f8](https://linux-hardware.org/?probe=5b3fb0b4f8) | Jun 09, 2023 |
| Digibras      | NH4CU03                     | [c66d30943e](https://linux-hardware.org/?probe=c66d30943e) | Jun 09, 2023 |
| Acer          | TravelMate P215-53          | [9536bf547a](https://linux-hardware.org/?probe=9536bf547a) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK U7411              | [ab35c95b72](https://linux-hardware.org/?probe=ab35c95b72) | Jun 09, 2023 |
| Acer          | TravelMate P449-G2-M        | [6b42200bee](https://linux-hardware.org/?probe=6b42200bee) | Jun 09, 2023 |
| HP            | G42                         | [fe8d2be276](https://linux-hardware.org/?probe=fe8d2be276) | Jun 08, 2023 |
| HP            | Laptop 14-cm0xxx            | [f1100ce875](https://linux-hardware.org/?probe=f1100ce875) | Jun 08, 2023 |
| HP            | G42                         | [4f33462d46](https://linux-hardware.org/?probe=4f33462d46) | Jun 08, 2023 |
| Acer          | TravelMate P449-G2-M        | [0fa009ad04](https://linux-hardware.org/?probe=0fa009ad04) | Jun 08, 2023 |
| MSI           | GE60 2PL                    | [e1d118e2d2](https://linux-hardware.org/?probe=e1d118e2d2) | Jun 08, 2023 |
| HP            | G62                         | [fb9522ceac](https://linux-hardware.org/?probe=fb9522ceac) | Jun 08, 2023 |
| Acer          | Aspire 7741                 | [09b2301e59](https://linux-hardware.org/?probe=09b2301e59) | Jun 08, 2023 |
| Lenovo        | ThinkPad X131e 3374A17      | [d992393271](https://linux-hardware.org/?probe=d992393271) | Jun 08, 2023 |
| Lenovo        | ThinkPad X131e 3374A17      | [dd385507aa](https://linux-hardware.org/?probe=dd385507aa) | Jun 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ef71a1641b](https://linux-hardware.org/?probe=ef71a1641b) | Jun 08, 2023 |
| HP            | Pavilion 17                 | [da809f90cc](https://linux-hardware.org/?probe=da809f90cc) | Jun 07, 2023 |
| Dell          | Latitude 5530               | [1e3452635f](https://linux-hardware.org/?probe=1e3452635f) | Jun 07, 2023 |
| HP            | ProBook 4530s               | [bdb6739deb](https://linux-hardware.org/?probe=bdb6739deb) | Jun 07, 2023 |
| Intel         | HURONRIVER                  | [57035a777c](https://linux-hardware.org/?probe=57035a777c) | Jun 07, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [490ae0bc1c](https://linux-hardware.org/?probe=490ae0bc1c) | Jun 07, 2023 |
| MSI           | Pulse GL66 12UDK            | [8c9a9eb310](https://linux-hardware.org/?probe=8c9a9eb310) | Jun 06, 2023 |
| HP            | Pavilion g7                 | [f8cccf0fec](https://linux-hardware.org/?probe=f8cccf0fec) | Jun 06, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [be9987ca28](https://linux-hardware.org/?probe=be9987ca28) | Jun 06, 2023 |
| Fujitsu       | FMVNA4NE-                   | [626a677331](https://linux-hardware.org/?probe=626a677331) | Jun 06, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [c20dd8572a](https://linux-hardware.org/?probe=c20dd8572a) | Jun 05, 2023 |
| HP            | ENVY Laptop 13-ba0xxx       | [22143d333a](https://linux-hardware.org/?probe=22143d333a) | Jun 05, 2023 |
| Aquarius      | NS585                       | [b3f11e4a53](https://linux-hardware.org/?probe=b3f11e4a53) | Jun 05, 2023 |
| Fujitsu       | FMVNA4NE-                   | [b1c1176a5b](https://linux-hardware.org/?probe=b1c1176a5b) | Jun 05, 2023 |
| Dell          | Latitude 3410               | [820e62c9d3](https://linux-hardware.org/?probe=820e62c9d3) | Jun 04, 2023 |
| MSI           | GL75 Leopard 10SER          | [24111ade43](https://linux-hardware.org/?probe=24111ade43) | Jun 04, 2023 |
| Dell          | Latitude 3410               | [12515d41c8](https://linux-hardware.org/?probe=12515d41c8) | Jun 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [1352a1d7c7](https://linux-hardware.org/?probe=1352a1d7c7) | Jun 04, 2023 |
| ASUSTek       | Q502LA                      | [679a477085](https://linux-hardware.org/?probe=679a477085) | Jun 04, 2023 |
| Clevo         | M670SRU                     | [0935f74d34](https://linux-hardware.org/?probe=0935f74d34) | Jun 04, 2023 |
| Clevo         | M670SRU                     | [e163d57d56](https://linux-hardware.org/?probe=e163d57d56) | Jun 04, 2023 |
| AVITA         | NS14A8                      | [a576b4d5cc](https://linux-hardware.org/?probe=a576b4d5cc) | Jun 04, 2023 |
| Dell          | Latitude 5420               | [9085f3c8f7](https://linux-hardware.org/?probe=9085f3c8f7) | Jun 04, 2023 |
| Toshiba       | WT8-A                       | [01e8918ef6](https://linux-hardware.org/?probe=01e8918ef6) | Jun 04, 2023 |
| Acer          | Aspire 5738                 | [138d22e03e](https://linux-hardware.org/?probe=138d22e03e) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [a10a42a44d](https://linux-hardware.org/?probe=a10a42a44d) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [e58b2a1237](https://linux-hardware.org/?probe=e58b2a1237) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [ce54d0192d](https://linux-hardware.org/?probe=ce54d0192d) | Jun 04, 2023 |
| Lenovo        | ThinkPad E420 1141R79       | [7f66bf0045](https://linux-hardware.org/?probe=7f66bf0045) | Jun 03, 2023 |
| Apple         | MacBookPro9,2               | [eb51cb6dcf](https://linux-hardware.org/?probe=eb51cb6dcf) | Jun 03, 2023 |
| Acer          | Aspire V3-372               | [1200863830](https://linux-hardware.org/?probe=1200863830) | Jun 03, 2023 |
| Acer          | Aspire A115-31              | [338f025bce](https://linux-hardware.org/?probe=338f025bce) | Jun 03, 2023 |
| Apple         | MacBookPro7,1               | [b1513dc005](https://linux-hardware.org/?probe=b1513dc005) | Jun 03, 2023 |
| HP            | Laptop 14-cm0xxx            | [8933e1b0ad](https://linux-hardware.org/?probe=8933e1b0ad) | Jun 03, 2023 |
| Acer          | Aspire E5-772G              | [5bd684bed6](https://linux-hardware.org/?probe=5bd684bed6) | Jun 02, 2023 |
| Acer          | Aspire E5-772G              | [f454cdf394](https://linux-hardware.org/?probe=f454cdf394) | Jun 02, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [b546b2e7f1](https://linux-hardware.org/?probe=b546b2e7f1) | Jun 02, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2a67b74a26](https://linux-hardware.org/?probe=2a67b74a26) | Jun 02, 2023 |
| Apple         | MacBookPro5,5               | [9bf36ef4a5](https://linux-hardware.org/?probe=9bf36ef4a5) | Jun 02, 2023 |
| HP            | ZBook 15 G6                 | [2f7bb21988](https://linux-hardware.org/?probe=2f7bb21988) | Jun 02, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [174ffa62e4](https://linux-hardware.org/?probe=174ffa62e4) | Jun 02, 2023 |
| Aquarius      | NS585                       | [6f93385917](https://linux-hardware.org/?probe=6f93385917) | Jun 02, 2023 |
| Dell          | Inspiron 5567               | [bd3a6c5bd8](https://linux-hardware.org/?probe=bd3a6c5bd8) | Jun 02, 2023 |
| Aquarius      | NS585                       | [091267ec3a](https://linux-hardware.org/?probe=091267ec3a) | Jun 02, 2023 |
| Aquarius      | NS585                       | [7534819f94](https://linux-hardware.org/?probe=7534819f94) | Jun 02, 2023 |
| Lenovo        | S40-70 80GQ                 | [9a3fbc7388](https://linux-hardware.org/?probe=9a3fbc7388) | Jun 02, 2023 |
| Dell          | Latitude E6430              | [b129765265](https://linux-hardware.org/?probe=b129765265) | Jun 02, 2023 |
| HP            | EliteBook 840 G6            | [81ec1cc134](https://linux-hardware.org/?probe=81ec1cc134) | Jun 01, 2023 |
| Dell          | Latitude E5510              | [4a0bc9e53f](https://linux-hardware.org/?probe=4a0bc9e53f) | Jun 01, 2023 |
| Dell          | System Inspiron N4110       | [ea09e45a4f](https://linux-hardware.org/?probe=ea09e45a4f) | Jun 01, 2023 |
| Aquarius      | NS585                       | [ffa7425b95](https://linux-hardware.org/?probe=ffa7425b95) | Jun 01, 2023 |
| Aquarius      | NS585                       | [fafcbbe90e](https://linux-hardware.org/?probe=fafcbbe90e) | Jun 01, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [ffc6b5e345](https://linux-hardware.org/?probe=ffc6b5e345) | Jun 01, 2023 |
| Dell          | Latitude E5510              | [9457826049](https://linux-hardware.org/?probe=9457826049) | Jun 01, 2023 |
| Positivo      | C500                        | [8dba4589fe](https://linux-hardware.org/?probe=8dba4589fe) | Jun 01, 2023 |
| ASUSTek       | X200LA                      | [ae3925153d](https://linux-hardware.org/?probe=ae3925153d) | May 31, 2023 |
| ASUSTek       | 1225B                       | [769a6736f1](https://linux-hardware.org/?probe=769a6736f1) | May 31, 2023 |
| Unknown       | Unknown                     | [412c6d4af8](https://linux-hardware.org/?probe=412c6d4af8) | May 31, 2023 |
| Fujitsu       | LIFEBOOK E780               | [8459f7cfee](https://linux-hardware.org/?probe=8459f7cfee) | May 31, 2023 |
| Apple         | MacBookPro16,1              | [717c7884c8](https://linux-hardware.org/?probe=717c7884c8) | May 31, 2023 |
| HP            | EliteBook 840 G4            | [46ccbd2d62](https://linux-hardware.org/?probe=46ccbd2d62) | May 31, 2023 |
| HP            | EliteBook 840 G4            | [b90cb27f97](https://linux-hardware.org/?probe=b90cb27f97) | May 31, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [5f8bd19e3d](https://linux-hardware.org/?probe=5f8bd19e3d) | May 31, 2023 |
| Acer          | TravelMate P449-G2-M        | [41177ef027](https://linux-hardware.org/?probe=41177ef027) | May 31, 2023 |
| Dell          | Latitude 5411               | [8583aa2091](https://linux-hardware.org/?probe=8583aa2091) | May 31, 2023 |
| ASUSTek       | K52Jc                       | [ad0b57d7c6](https://linux-hardware.org/?probe=ad0b57d7c6) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | [e065b72b88](https://linux-hardware.org/?probe=e065b72b88) | May 31, 2023 |
| ASUSTek       | K52Jc                       | [7709d9fd16](https://linux-hardware.org/?probe=7709d9fd16) | May 31, 2023 |
| Dell          | Latitude E5510              | [52e1023195](https://linux-hardware.org/?probe=52e1023195) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | [52047d2230](https://linux-hardware.org/?probe=52047d2230) | May 31, 2023 |
| Dell          | Latitude E5510              | [aa0f6a81b6](https://linux-hardware.org/?probe=aa0f6a81b6) | May 30, 2023 |
| HP            | Laptop 17-ca0xxx            | [3222c41173](https://linux-hardware.org/?probe=3222c41173) | May 30, 2023 |
| Chuwi         | HeroBook Air                | [80afc31c99](https://linux-hardware.org/?probe=80afc31c99) | May 30, 2023 |
| Lenovo        | ThinkPad T460 20FMS4LL00    | [7519448ca8](https://linux-hardware.org/?probe=7519448ca8) | May 30, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [ad3464fd76](https://linux-hardware.org/?probe=ad3464fd76) | May 30, 2023 |
| Acer          | Aspire A315-58              | [66de62e958](https://linux-hardware.org/?probe=66de62e958) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [c8e0efc288](https://linux-hardware.org/?probe=c8e0efc288) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [da399dc7cc](https://linux-hardware.org/?probe=da399dc7cc) | May 29, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Debian 11                       | 3369      | 58.37%  |
| Debian 10                       | 855       | 14.81%  |
| Debian 12                       | 707       | 12.25%  |
| Debian Testing                  | 357       | 6.19%   |
| Debian                          | 159       | 2.75%   |
| Debian 9                        | 146       | 2.53%   |
| Debian Unstable                 | 128       | 2.22%   |
| Debian 11-updates               | 27        | 0.47%   |
| Debian 8                        | 11        | 0.19%   |
| Debian Sid                      | 4         | 0.07%   |
| Debian 22                       | 3         | 0.05%   |
| Debian Testing/unstable         | 2         | 0.03%   |
| Debian 23                       | 2         | 0.03%   |
| Debian Testing-proposed-updates | 1         | 0.02%   |
| Debian 99                       | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Debian | 5525      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Notebooks | Percent |
|-----------------|-----------|---------|
| 5.10.0-8-amd64  | 586       | 9.26%   |
| 5.10.0-10-amd64 | 491       | 7.76%   |
| 5.10.0-20-amd64 | 244       | 3.85%   |
| 5.10.0-21-amd64 | 240       | 3.79%   |
| 5.10.0-18-amd64 | 177       | 2.8%    |
| 5.10.0-9-amd64  | 173       | 2.73%   |
| 6.1.0-9-amd64   | 172       | 2.72%   |
| 5.10.0-7-amd64  | 171       | 2.7%    |
| 5.10.0-16-amd64 | 167       | 2.64%   |
| 5.10.0-19-amd64 | 162       | 2.56%   |
| 6.1.0-10-amd64  | 161       | 2.54%   |
| 5.10.0-13-amd64 | 151       | 2.39%   |
| 5.10.0-23-amd64 | 106       | 1.67%   |
| 5.10.0-11-amd64 | 105       | 1.66%   |
| 6.1.0-11-amd64  | 103       | 1.63%   |
| 4.19.0-9-amd64  | 85        | 1.34%   |
| 4.19.0-6-amd64  | 82        | 1.3%    |
| 5.10.0-14-amd64 | 80        | 1.26%   |
| 5.10.0-17-amd64 | 73        | 1.15%   |
| 4.19.0-13-amd64 | 69        | 1.09%   |
| 4.19.0-8-amd64  | 68        | 1.07%   |
| 6.1.0-12-amd64  | 63        | 1%      |
| 5.10.0-15-amd64 | 53        | 0.84%   |
| 4.19.0-16-amd64 | 53        | 0.84%   |
| 6.1.0-7-amd64   | 52        | 0.82%   |
| 4.19.0-10-amd64 | 52        | 0.82%   |
| 5.15.0-2-amd64  | 51        | 0.81%   |
| 5.10.0-2-amd64  | 49        | 0.77%   |
| 4.19.0-12-amd64 | 47        | 0.74%   |
| 6.1.0-4-amd64   | 44        | 0.69%   |
| 5.10.0-22-amd64 | 43        | 0.68%   |
| 4.19.0-14-amd64 | 42        | 0.66%   |
| 5.10.0-6-amd64  | 41        | 0.65%   |
| 5.10.0-12-amd64 | 40        | 0.63%   |
| 4.19.0-17-amd64 | 40        | 0.63%   |
| 4.9.0-8-amd64   | 39        | 0.62%   |
| 5.18.0-2-amd64  | 31        | 0.49%   |
| 5.10.0-3-amd64  | 31        | 0.49%   |
| 6.1.0-6-amd64   | 28        | 0.44%   |
| 6.0.0-6-amd64   | 27        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 3161      | 53.45%  |
| 6.1.0    | 707       | 11.95%  |
| 4.19.0   | 656       | 11.09%  |
| 6.0.0    | 147       | 2.49%   |
| 4.9.0    | 120       | 2.03%   |
| 5.18.0   | 108       | 1.83%   |
| 5.15.0   | 92        | 1.56%   |
| 5.9.0    | 74        | 1.25%   |
| 5.19.0   | 70        | 1.18%   |
| 5.16.0   | 69        | 1.17%   |
| 5.4.0    | 65        | 1.1%    |
| 5.7.0    | 59        | 1%      |
| 5.8.0    | 56        | 0.95%   |
| 5.14.0   | 53        | 0.9%    |
| 5.6.0    | 45        | 0.76%   |
| 5.17.0   | 39        | 0.66%   |
| 6.4.0    | 32        | 0.54%   |
| 6.3.0    | 29        | 0.49%   |
| 5.3.0    | 19        | 0.32%   |
| 5.5.0    | 16        | 0.27%   |
| 5.2.0    | 12        | 0.2%    |
| 4.18.0   | 12        | 0.2%    |
| 3.16.0   | 9         | 0.15%   |
| 6.2.16   | 7         | 0.12%   |
| 6.5.0    | 6         | 0.1%    |
| 5.12.0   | 6         | 0.1%    |
| 5.10.10  | 4         | 0.07%   |
| 6.4.3    | 3         | 0.05%   |
| 6.4.2    | 3         | 0.05%   |
| 6.3.4    | 3         | 0.05%   |
| 6.2.8    | 3         | 0.05%   |
| 6.1.15   | 3         | 0.05%   |
| 5.3.5    | 3         | 0.05%   |
| 5.17.5   | 3         | 0.05%   |
| 5.15.107 | 3         | 0.05%   |
| 5.13.19  | 3         | 0.05%   |
| 5.13.0   | 3         | 0.05%   |
| 5.11.0   | 3         | 0.05%   |
| 5.10.60  | 3         | 0.05%   |
| 5.10.181 | 3         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 3189      | 54.03%  |
| 6.1     | 719       | 12.18%  |
| 4.19    | 660       | 11.18%  |
| 6.0     | 155       | 2.63%   |
| 4.9     | 123       | 2.08%   |
| 5.15    | 119       | 2.02%   |
| 5.18    | 113       | 1.91%   |
| 5.9     | 80        | 1.36%   |
| 5.4     | 77        | 1.3%    |
| 5.19    | 75        | 1.27%   |
| 5.16    | 73        | 1.24%   |
| 5.7     | 62        | 1.05%   |
| 5.8     | 61        | 1.03%   |
| 5.14    | 58        | 0.98%   |
| 5.6     | 49        | 0.83%   |
| 5.17    | 48        | 0.81%   |
| 6.4     | 45        | 0.76%   |
| 6.3     | 37        | 0.63%   |
| 5.3     | 24        | 0.41%   |
| 5.5     | 19        | 0.32%   |
| 5.2     | 18        | 0.3%    |
| 6.2     | 15        | 0.25%   |
| 5.13    | 12        | 0.2%    |
| 4.18    | 12        | 0.2%    |
| 5.12    | 9         | 0.15%   |
| 5.11    | 9         | 0.15%   |
| 3.16    | 9         | 0.15%   |
| 6.5     | 7         | 0.12%   |
| 3.10    | 4         | 0.07%   |
| 5.1     | 3         | 0.05%   |
| 5.0     | 3         | 0.05%   |
| 4.17    | 2         | 0.03%   |
| 4.15    | 2         | 0.03%   |
| 4.14    | 2         | 0.03%   |
| 5.4.104 | 1         | 0.02%   |
| 5.15.6  | 1         | 0.02%   |
| 4.4     | 1         | 0.02%   |
| 4.20    | 1         | 0.02%   |
| 4.13    | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 5279      | 95.53%  |
| i686    | 232       | 4.2%    |
| armv7l  | 10        | 0.18%   |
| aarch64 | 4         | 0.07%   |
| i586    | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 1580      | 27.85%  |
| Unknown           | 1285      | 22.65%  |
| KDE5              | 781       | 13.76%  |
| XFCE              | 752       | 13.25%  |
| MATE              | 245       | 4.32%   |
| X-Cinnamon        | 218       | 3.84%   |
| LXDE              | 169       | 2.98%   |
| Cinnamon          | 153       | 2.7%    |
| KDE               | 116       | 2.04%   |
| i3                | 102       | 1.8%    |
| lxqt              | 85        | 1.5%    |
| GNOME Flashback   | 39        | 0.69%   |
| lightdm-xsession  | 29        | 0.51%   |
| Budgie            | 17        | 0.3%    |
| Openbox           | 16        | 0.28%   |
| GNOME Classic     | 15        | 0.26%   |
| Trinity           | 14        | 0.25%   |
| sway              | 5         | 0.09%   |
| Enlightenment     | 5         | 0.09%   |
| dwm               | 5         | 0.09%   |
| bspwm             | 5         | 0.09%   |
| awesome           | 5         | 0.09%   |
| ICEWM             | 4         | 0.07%   |
| Fluxbox           | 4         | 0.07%   |
| Cutefish          | 3         | 0.05%   |
| BunsenLabs        | 3         | 0.05%   |
| xmonad            | 2         | 0.04%   |
| x-session-manager | 2         | 0.04%   |
| Unity             | 2         | 0.04%   |
| KDE4              | 2         | 0.04%   |
| GNUstep           | 2         | 0.04%   |
| default           | 2         | 0.04%   |
| wmaker-common     | 1         | 0.02%   |
| Pantheon          | 1         | 0.02%   |
| mwm               | 1         | 0.02%   |
| matchbox          | 1         | 0.02%   |
| jwm               | 1         | 0.02%   |
| i3-gaps           | 1         | 0.02%   |
| Deepin            | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 3155      | 55.88%  |
| Wayland     | 1236      | 21.89%  |
| Unknown     | 1021      | 18.08%  |
| Tty         | 229       | 4.06%   |
| Unspecified | 4         | 0.07%   |
| Web         | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2138      | 37.64%  |
| GDM     | 1003      | 17.66%  |
| LightDM | 996       | 17.54%  |
| SDDM    | 718       | 12.64%  |
| GDM3    | 446       | 7.85%   |
| TDM     | 310       | 5.46%   |
| XDM     | 21        | 0.37%   |
| SLiM    | 13        | 0.23%   |
| NODM    | 10        | 0.18%   |
| LXDM    | 8         | 0.14%   |
| KDM     | 8         | 0.14%   |
| Ly      | 4         | 0.07%   |
| GREETD  | 3         | 0.05%   |
| WDM     | 1         | 0.02%   |
| SU      | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1749      | 31.18%  |
| Unknown | 1007      | 17.95%  |
| ru_RU   | 378       | 6.74%   |
| de_DE   | 370       | 6.6%    |
| fr_FR   | 311       | 5.54%   |
| en_GB   | 257       | 4.58%   |
| pt_BR   | 191       | 3.4%    |
| es_ES   | 154       | 2.75%   |
| it_IT   | 149       | 2.66%   |
| pl_PL   | 110       | 1.96%   |
| en_CA   | 69        | 1.23%   |
| C       | 59        | 1.05%   |
| es_MX   | 53        | 0.94%   |
| en_AU   | 53        | 0.94%   |
| en_IN   | 51        | 0.91%   |
| zh_CN   | 48        | 0.86%   |
| es_AR   | 39        | 0.7%    |
| en_IE   | 34        | 0.61%   |
| es_CL   | 32        | 0.57%   |
| sv_SE   | 30        | 0.53%   |
| hu_HU   | 30        | 0.53%   |
| de_CH   | 21        | 0.37%   |
| es_VE   | 20        | 0.36%   |
| pt_PT   | 19        | 0.34%   |
| nl_NL   | 19        | 0.34%   |
| fi_FI   | 19        | 0.34%   |
| de_AT   | 19        | 0.34%   |
| cs_CZ   | 18        | 0.32%   |
| es_CO   | 17        | 0.3%    |
| tr_TR   | 16        | 0.29%   |
| en_NZ   | 15        | 0.27%   |
| ja_JP   | 14        | 0.25%   |
| en_ZA   | 13        | 0.23%   |
| fr_BE   | 12        | 0.21%   |
| ca_ES   | 12        | 0.21%   |
| ko_KR   | 11        | 0.2%    |
| en_SG   | 11        | 0.2%    |
| zh_TW   | 10        | 0.18%   |
| sk_SK   | 10        | 0.18%   |
| fr_CH   | 10        | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 3413      | 61.1%   |
| BIOS | 2173      | 38.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 4040      | 72.69%  |
| Overlay | 1122      | 20.19%  |
| Btrfs   | 184       | 3.31%   |
| Unknown | 78        | 1.4%    |
| Xfs     | 50        | 0.9%    |
| Tmpfs   | 27        | 0.49%   |
| Zfs     | 18        | 0.32%   |
| Ext2    | 16        | 0.29%   |
| Rootfs  | 10        | 0.18%   |
| Ext3    | 8         | 0.14%   |
| Aufs    | 4         | 0.07%   |
| F2fs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 3452      | 61.52%  |
| Unknown | 1095      | 19.52%  |
| MBR     | 1064      | 18.96%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4652      | 83.07%  |
| Yes       | 948       | 16.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4148      | 74.22%  |
| Yes       | 1441      | 25.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1234      | 22.33%  |
| Hewlett-Packard        | 837       | 15.15%  |
| Dell                   | 806       | 14.59%  |
| Apple                  | 666       | 12.05%  |
| ASUSTek Computer       | 505       | 9.14%   |
| Acer                   | 388       | 7.02%   |
| Google                 | 155       | 2.81%   |
| Toshiba                | 95        | 1.72%   |
| MSI                    | 94        | 1.7%    |
| Samsung Electronics    | 83        | 1.5%    |
| Sony                   | 48        | 0.87%   |
| Aquarius               | 48        | 0.87%   |
| HUAWEI                 | 46        | 0.83%   |
| Unknown                | 46        | 0.83%   |
| Notebook               | 32        | 0.58%   |
| Fujitsu                | 32        | 0.58%   |
| Medion                 | 17        | 0.31%   |
| Alienware              | 17        | 0.31%   |
| Panasonic              | 16        | 0.29%   |
| Positivo               | 15        | 0.27%   |
| Packard Bell           | 14        | 0.25%   |
| Intel                  | 14        | 0.25%   |
| TUXEDO                 | 13        | 0.24%   |
| Timi                   | 13        | 0.24%   |
| IBM                    | 13        | 0.24%   |
| LG Electronics         | 11        | 0.2%    |
| HONOR                  | 11        | 0.2%    |
| Clevo                  | 11        | 0.2%    |
| Fujitsu Siemens        | 9         | 0.16%   |
| PC Specialist          | 8         | 0.14%   |
| eMachines              | 8         | 0.14%   |
| Razer                  | 7         | 0.13%   |
| GPU Company            | 7         | 0.13%   |
| Gigabyte Technology    | 7         | 0.13%   |
| Framework              | 7         | 0.13%   |
| System76               | 6         | 0.11%   |
| SLIMBOOK               | 6         | 0.11%   |
| Chuwi                  | 6         | 0.11%   |
| Avell High Performance | 6         | 0.11%   |
| Schenker               | 5         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBook5,2                      | 355       | 6.43%   |
| Apple MacBookAir7,2                   | 80        | 1.45%   |
| Apple MacBookAir7,1                   | 77        | 1.39%   |
| Google Enguarde                       | 74        | 1.34%   |
| Unknown                               | 61        | 1.1%    |
| Apple MacBook2,1                      | 57        | 1.03%   |
| Aquarius NS585                        | 48        | 0.87%   |
| HP Notebook                           | 28        | 0.51%   |
| Lenovo ThinkPad E475 20H40006US       | 24        | 0.43%   |
| Google Terra                          | 23        | 0.42%   |
| Apple MacBook4,1                      | 23        | 0.42%   |
| HP Pavilion g6                        | 17        | 0.31%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US | 16        | 0.29%   |
| Acer Aspire A315-23                   | 16        | 0.29%   |
| ASUS 1005HA                           | 15        | 0.27%   |
| HP EliteBook 840 G3                   | 14        | 0.25%   |
| Google Reks                           | 14        | 0.25%   |
| HP Laptop 15-db0xxx                   | 13        | 0.24%   |
| Dell Latitude E7440                   | 13        | 0.24%   |
| Dell Latitude 7480                    | 13        | 0.24%   |
| Dell Latitude E6430                   | 12        | 0.22%   |
| HP Pavilion dv6                       | 11        | 0.2%    |
| HP EliteBook 8460p                    | 11        | 0.2%    |
| HP 255 G8 Notebook PC                 | 11        | 0.2%    |
| Dell Latitude E7450                   | 11        | 0.2%    |
| Dell Inspiron 5570                    | 11        | 0.2%    |
| Acer Aspire A515-56                   | 11        | 0.2%    |
| HP Laptop 15s-eq2xxx                  | 10        | 0.18%   |
| HP 250 G7 Notebook PC                 | 10        | 0.18%   |
| Dell Latitude E6420                   | 10        | 0.18%   |
| Dell Latitude 5420                    | 10        | 0.18%   |
| HP Pavilion Notebook                  | 9         | 0.16%   |
| Dell XPS 13 9310                      | 9         | 0.16%   |
| Dell Inspiron 15-3567                 | 9         | 0.16%   |
| Samsung 300E4C/300E5C/300E7C          | 8         | 0.14%   |
| HP Pavilion Gaming Laptop 15-ec2xxx   | 8         | 0.14%   |
| HP Laptop 15-db1xxx                   | 8         | 0.14%   |
| HP EliteBook 845 G8 Notebook PC       | 8         | 0.14%   |
| HP EliteBook 840 G1                   | 8         | 0.14%   |
| Dell XPS 13 9370                      | 8         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 809       | 14.64%  |
| Apple MacBook5    | 356       | 6.44%   |
| Dell Latitude     | 317       | 5.74%   |
| Acer Aspire       | 252       | 4.56%   |
| Dell Inspiron     | 232       | 4.2%    |
| Lenovo IdeaPad    | 219       | 3.96%   |
| HP EliteBook      | 175       | 3.17%   |
| Apple MacBookAir7 | 157       | 2.84%   |
| HP Pavilion       | 128       | 2.32%   |
| HP Laptop         | 116       | 2.1%    |
| HP ProBook        | 108       | 1.95%   |
| Dell XPS          | 90        | 1.63%   |
| ASUS VivoBook     | 79        | 1.43%   |
| Toshiba Satellite | 74        | 1.34%   |
| Google Enguarde   | 74        | 1.34%   |
| Dell Vostro       | 67        | 1.21%   |
| Dell Precision    | 62        | 1.12%   |
| Unknown           | 61        | 1.1%    |
| Apple MacBook2    | 57        | 1.03%   |
| Aquarius NS585    | 48        | 0.87%   |
| HP Compaq         | 45        | 0.81%   |
| HP ZBook          | 36        | 0.65%   |
| HP 250            | 36        | 0.65%   |
| ASUS ZenBook      | 36        | 0.65%   |
| Lenovo Legion     | 33        | 0.6%    |
| ASUS ASUS         | 32        | 0.58%   |
| Acer TravelMate   | 32        | 0.58%   |
| Acer Nitro        | 30        | 0.54%   |
| HP Notebook       | 28        | 0.51%   |
| Fujitsu LIFEBOOK  | 28        | 0.51%   |
| Acer Swift        | 28        | 0.51%   |
| Lenovo ThinkBook  | 26        | 0.47%   |
| HP 255            | 25        | 0.45%   |
| Google Terra      | 23        | 0.42%   |
| Apple MacBook4    | 23        | 0.42%   |
| ASUS ROG          | 22        | 0.4%    |
| HP ENVY           | 20        | 0.36%   |
| HP OMEN           | 19        | 0.34%   |
| Lenovo Yoga       | 17        | 0.31%   |
| ASUS TUF          | 17        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 522       | 9.45%   |
| 2009    | 513       | 9.29%   |
| 2021    | 502       | 9.09%   |
| 2020    | 502       | 9.09%   |
| 2018    | 352       | 6.37%   |
| 2012    | 349       | 6.32%   |
| 2017    | 337       | 6.1%    |
| 2011    | 337       | 6.1%    |
| 2016    | 333       | 6.03%   |
| 2015    | 298       | 5.39%   |
| 2013    | 282       | 5.1%    |
| 2014    | 272       | 4.92%   |
| 2022    | 263       | 4.76%   |
| 2010    | 210       | 3.8%    |
| 2008    | 172       | 3.11%   |
| 2007    | 136       | 2.46%   |
| 2023    | 42        | 0.76%   |
| 2006    | 37        | 0.67%   |
| 2005    | 26        | 0.47%   |
| Unknown | 16        | 0.29%   |
| 2004    | 11        | 0.2%    |
| 2003    | 11        | 0.2%    |
| 2002    | 2         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 5525      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 5081      | 91.48%  |
| Enabled  | 473       | 8.52%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5354      | 96.89%  |
| Yes  | 172       | 3.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1463      | 26.23%  |
| 3.01-4.0    | 1042      | 18.68%  |
| 16.01-24.0  | 919       | 16.48%  |
| 8.01-16.0   | 885       | 15.87%  |
| 1.01-2.0    | 584       | 10.47%  |
| 32.01-64.0  | 340       | 6.1%    |
| 2.01-3.0    | 111       | 1.99%   |
| 0.51-1.0    | 86        | 1.54%   |
| 64.01-256.0 | 67        | 1.2%    |
| 24.01-32.0  | 57        | 1.02%   |
| 0.01-0.5    | 21        | 0.38%   |
| Unknown     | 2         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2210      | 37.23%  |
| 2.01-3.0   | 1260      | 21.23%  |
| 4.01-8.0   | 834       | 14.05%  |
| 3.01-4.0   | 660       | 11.12%  |
| 0.51-1.0   | 568       | 9.57%   |
| 8.01-16.0  | 224       | 3.77%   |
| 0.01-0.5   | 142       | 2.39%   |
| 16.01-24.0 | 22        | 0.37%   |
| Unknown    | 7         | 0.12%   |
| 32.01-64.0 | 4         | 0.07%   |
| 24.01-32.0 | 4         | 0.07%   |
| 0          | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4340      | 77.38%  |
| 2      | 1077      | 19.2%   |
| 3      | 130       | 2.32%   |
| 0      | 35        | 0.62%   |
| 4      | 20        | 0.36%   |
| 5      | 5         | 0.09%   |
| 7      | 2         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3685      | 66.43%  |
| Yes       | 1862      | 33.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4505      | 81.24%  |
| No        | 1040      | 18.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5409      | 97.81%  |
| No        | 121       | 2.19%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4450      | 79.98%  |
| No        | 1114      | 20.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 1366      | 24.55%  |
| Germany     | 539       | 9.69%   |
| Russia      | 438       | 7.87%   |
| France      | 383       | 6.88%   |
| Brazil      | 278       | 5%      |
| Spain       | 226       | 4.06%   |
| Italy       | 208       | 3.74%   |
| Poland      | 162       | 2.91%   |
| UK          | 129       | 2.32%   |
| Canada      | 100       | 1.8%    |
| Netherlands | 97        | 1.74%   |
| Mexico      | 76        | 1.37%   |
| Switzerland | 74        | 1.33%   |
| India       | 74        | 1.33%   |
| Sweden      | 71        | 1.28%   |
| China       | 68        | 1.22%   |
| Australia   | 64        | 1.15%   |
| Argentina   | 62        | 1.11%   |
| Ukraine     | 59        | 1.06%   |
| Turkey      | 56        | 1.01%   |
| Hungary     | 50        | 0.9%    |
| Portugal    | 46        | 0.83%   |
| Austria     | 46        | 0.83%   |
| Belgium     | 45        | 0.81%   |
| Czechia     | 41        | 0.74%   |
| Chile       | 39        | 0.7%    |
| Finland     | 38        | 0.68%   |
| Greece      | 36        | 0.65%   |
| Norway      | 35        | 0.63%   |
| Romania     | 34        | 0.61%   |
| Indonesia   | 30        | 0.54%   |
| Colombia    | 29        | 0.52%   |
| Ireland     | 28        | 0.5%    |
| Japan       | 25        | 0.45%   |
| Venezuela   | 24        | 0.43%   |
| New Zealand | 21        | 0.38%   |
| Bulgaria    | 21        | 0.38%   |
| Thailand    | 19        | 0.34%   |
| Denmark     | 19        | 0.34%   |
| Belarus     | 18        | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Bangor            | 632       | 10.72%  |
| Dover-Foxcroft    | 229       | 3.89%   |
| Voronezh          | 164       | 2.78%   |
| Moscow            | 78        | 1.32%   |
| Paris             | 67        | 1.14%   |
| St Petersburg     | 55        | 0.93%   |
| Berlin            | 54        | 0.92%   |
| Madrid            | 43        | 0.73%   |
| Warsaw            | 39        | 0.66%   |
| Seville           | 39        | 0.66%   |
| Sao Paulo         | 38        | 0.64%   |
| Munich            | 33        | 0.56%   |
| Vienna            | 32        | 0.54%   |
| Milan             | 29        | 0.49%   |
| Amsterdam         | 29        | 0.49%   |
| Hamburg           | 28        | 0.48%   |
| London            | 23        | 0.39%   |
| Barcelona         | 23        | 0.39%   |
| Prague            | 22        | 0.37%   |
| Istanbul          | 21        | 0.36%   |
| Frankfurt am Main | 21        | 0.36%   |
| Dublin            | 20        | 0.34%   |
| Budapest          | 20        | 0.34%   |
| Sydney            | 19        | 0.32%   |
| Brasília         | 19        | 0.32%   |
| Athens            | 19        | 0.32%   |
| Zurich            | 18        | 0.31%   |
| Helsinki          | 18        | 0.31%   |
| Toronto           | 17        | 0.29%   |
| Perm              | 16        | 0.27%   |
| Mexico City       | 16        | 0.27%   |
| Lisbon            | 16        | 0.27%   |
| Singapore         | 15        | 0.25%   |
| Saltsjoe-Boo      | 15        | 0.25%   |
| Melbourne         | 15        | 0.25%   |
| Rome              | 14        | 0.24%   |
| Cologne           | 14        | 0.24%   |
| Santiago          | 13        | 0.22%   |
| San Jose          | 13        | 0.22%   |
| Leipzig           | 13        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1006      | 1278   | 15.05%  |
| WDC                         | 745       | 923    | 11.15%  |
| Seagate                     | 591       | 704    | 8.84%   |
| Toshiba                     | 499       | 557    | 7.47%   |
| Unknown                     | 425       | 565    | 6.36%   |
| Kingston                    | 361       | 438    | 5.4%    |
| SanDisk                     | 337       | 420    | 5.04%   |
| Fujitsu                     | 294       | 304    | 4.4%    |
| SK hynix                    | 270       | 326    | 4.04%   |
| Crucial                     | 255       | 309    | 3.82%   |
| Apple                       | 193       | 247    | 2.89%   |
| Hitachi                     | 179       | 205    | 2.68%   |
| Micron Technology           | 171       | 186    | 2.56%   |
| Intel                       | 166       | 205    | 2.48%   |
| A-DATA Technology           | 144       | 277    | 2.15%   |
| HGST                        | 135       | 155    | 2.02%   |
| KIOXIA                      | 73        | 87     | 1.09%   |
| China                       | 41        | 47     | 0.61%   |
| LITEON                      | 38        | 46     | 0.57%   |
| Unknown                     | 37        | 41     | 0.55%   |
| Intenso                     | 31        | 40     | 0.46%   |
| Transcend                   | 29        | 36     | 0.43%   |
| SPCC                        | 29        | 36     | 0.43%   |
| Silicon Motion              | 28        | 33     | 0.42%   |
| PNY                         | 28        | 35     | 0.42%   |
| Phison                      | 27        | 36     | 0.4%    |
| Patriot                     | 24        | 26     | 0.36%   |
| SSSTC                       | 22        | 22     | 0.33%   |
| JMicron Technology          | 22        | 23     | 0.33%   |
| LITEONIT                    | 20        | 24     | 0.3%    |
| Team                        | 19        | 21     | 0.28%   |
| SABRENT                     | 18        | 19     | 0.27%   |
| Netac                       | 14        | 19     | 0.21%   |
| Micron/Crucial Technology   | 14        | 14     | 0.21%   |
| GOODRAM                     | 14        | 16     | 0.21%   |
| OCZ                         | 13        | 15     | 0.19%   |
| Kingston Technology Company | 12        | 13     | 0.18%   |
| ADATA Technology            | 12        | 12     | 0.18%   |
| Hewlett-Packard             | 11        | 13     | 0.16%   |
| Gigabyte Technology         | 11        | 13     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB                      | 238       | 3.48%   |
| Apple SSD AP0128H 121GB                             | 77        | 1.12%   |
| Seagate ST1000LM035-1RK172 1TB                      | 76        | 1.11%   |
| Apple SSD SM0128G 121GB                             | 74        | 1.08%   |
| Kingston SA400S37240G 240GB SSD                     | 66        | 0.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 61        | 0.89%   |
| Kingston SA400S37120G 120GB SSD                     | 57        | 0.83%   |
| Toshiba MK1655GSXF 160GB                            | 52        | 0.76%   |
| A-DATA SU800 512GB SSD                              | 50        | 0.73%   |
| Toshiba MQ01ABD100 1TB                              | 49        | 0.72%   |
| HGST HTS721010A9E630 1TB                            | 48        | 0.7%    |
| Toshiba MK1653GSX 160GB                             | 43        | 0.63%   |
| Crucial CT500MX500SSD1 500GB                        | 43        | 0.63%   |
| Toshiba MQ04ABF100 1TB                              | 42        | 0.61%   |
| Toshiba MQ01ABF050 500GB                            | 42        | 0.61%   |
| Unknown AGND3R  16GB                                | 39        | 0.57%   |
| Unknown MMC Card  32GB                              | 38        | 0.55%   |
| Unknown                                             | 37        | 0.54%   |
| Kingston SA400S37480G 480GB SSD                     | 36        | 0.53%   |
| Samsung SSD 860 EVO 500GB                           | 35        | 0.51%   |
| Samsung SSD 850 EVO 250GB                           | 34        | 0.5%    |
| Unknown HAG2e  16GB                                 | 32        | 0.47%   |
| Samsung SSD 970 EVO Plus 1TB                        | 32        | 0.47%   |
| Crucial CT1000MX500SSD1 1TB                         | 30        | 0.44%   |
| Seagate ST500LT012-1DG142 500GB                     | 29        | 0.42%   |
| Seagate ST1000LM048-2E7172 1TB                      | 29        | 0.42%   |
| Unknown MMC Card  64GB                              | 26        | 0.38%   |
| Samsung SSD 860 EVO 1TB                             | 26        | 0.38%   |
| Unknown SDW16G  16GB                                | 25        | 0.37%   |
| Seagate ST9500325AS 500GB                           | 24        | 0.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 23        | 0.34%   |
| Samsung SSD 980 1TB                                 | 23        | 0.34%   |
| Samsung SSD 860 EVO 250GB                           | 23        | 0.34%   |
| Kingston SV300S37A120G 120GB SSD                    | 23        | 0.34%   |
| HGST HTS725050A7E630 500GB                          | 23        | 0.34%   |
| Crucial CT240BX500SSD1 240GB                        | 23        | 0.34%   |
| Samsung SSD 850 EVO 500GB                           | 22        | 0.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 22        | 0.32%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 20        | 0.29%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                | 20        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 570       | 679    | 27.66%  |
| WDC                 | 424       | 488    | 20.57%  |
| Toshiba             | 360       | 395    | 17.47%  |
| Fujitsu             | 294       | 304    | 14.26%  |
| Hitachi             | 179       | 205    | 8.69%   |
| HGST                | 135       | 155    | 6.55%   |
| Samsung Electronics | 37        | 39     | 1.8%    |
| SABRENT             | 18        | 19     | 0.87%   |
| Unknown             | 17        | 20     | 0.82%   |
| IBM/Hitachi         | 5         | 6      | 0.24%   |
| Intenso             | 4         | 5      | 0.19%   |
| Apple               | 3         | 4      | 0.15%   |
| SILICONMOTION       | 2         | 2      | 0.1%    |
| ASMT                | 2         | 7      | 0.1%    |
| WALRAM              | 1         | 1      | 0.05%   |
| USB3.0              | 1         | 1      | 0.05%   |
| Unknown (CF)        | 1         | 1      | 0.05%   |
| SYMTEC              | 1         | 1      | 0.05%   |
| Space ke            | 1         | 1      | 0.05%   |
| SAGE                | 1         | 1      | 0.05%   |
| QNAP                | 1         | 2      | 0.05%   |
| Maxone              | 1         | 1      | 0.05%   |
| IBM                 | 1         | 1      | 0.05%   |
| Hewlett-Packard     | 1         | 1      | 0.05%   |
| External            | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 433       | 539    | 19.97%  |
| Kingston            | 276       | 348    | 12.73%  |
| Crucial             | 226       | 276    | 10.42%  |
| SanDisk             | 224       | 292    | 10.33%  |
| A-DATA Technology   | 106       | 223    | 4.89%   |
| Apple               | 103       | 119    | 4.75%   |
| WDC                 | 95        | 123    | 4.38%   |
| Micron Technology   | 63        | 69     | 2.91%   |
| SK hynix            | 52        | 60     | 2.4%    |
| Intel               | 49        | 54     | 2.26%   |
| China               | 41        | 47     | 1.89%   |
| Toshiba             | 37        | 41     | 1.71%   |
| LITEON              | 32        | 37     | 1.48%   |
| Transcend           | 26        | 33     | 1.2%    |
| Intenso             | 25        | 32     | 1.15%   |
| PNY                 | 24        | 30     | 1.11%   |
| SPCC                | 22        | 28     | 1.01%   |
| Patriot             | 21        | 23     | 0.97%   |
| LITEONIT            | 20        | 24     | 0.92%   |
| Team                | 17        | 19     | 0.78%   |
| OCZ                 | 13        | 15     | 0.6%    |
| Netac               | 13        | 18     | 0.6%    |
| JMicron Technology  | 12        | 12     | 0.55%   |
| GOODRAM             | 11        | 13     | 0.51%   |
| Plextor             | 9         | 9      | 0.42%   |
| Lexar               | 9         | 10     | 0.42%   |
| KingSpec            | 9         | 9      | 0.42%   |
| LDLC                | 8         | 8      | 0.37%   |
| Apacer              | 8         | 8      | 0.37%   |
| Unknown             | 8         | 8      | 0.37%   |
| KingDian            | 7         | 7      | 0.32%   |
| Hewlett-Packard     | 7         | 10     | 0.32%   |
| Seagate             | 6         | 6      | 0.28%   |
| Gigabyte Technology | 6         | 6      | 0.28%   |
| Corsair             | 6         | 6      | 0.28%   |
| ASMT                | 6         | 8      | 0.28%   |
| TO Exter            | 5         | 6      | 0.23%   |
| KIOXIA-EXCERIA      | 5         | 6      | 0.23%   |
| Dogfish             | 5         | 8      | 0.23%   |
| Lenovo              | 4         | 4      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 2016      | 2742   | 31.53%  |
| HDD     | 2009      | 2340   | 31.42%  |
| NVMe    | 1851      | 2429   | 28.95%  |
| MMC     | 453       | 596    | 7.09%   |
| Unknown | 64        | 72     | 1%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3621      | 4899   | 59.11%  |
| NVMe | 1851      | 2421   | 30.22%  |
| MMC  | 453       | 596    | 7.39%   |
| SAS  | 201       | 263    | 3.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2822      | 3556   | 71.08%  |
| 0.51-1.0   | 1031      | 1375   | 25.97%  |
| 1.01-2.0   | 87        | 109    | 2.19%   |
| 4.01-10.0  | 16        | 20     | 0.4%    |
| 3.01-4.0   | 10        | 17     | 0.25%   |
| 2.01-3.0   | 4         | 5      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1598      | 27.9%   |
| 251-500        | 1241      | 21.67%  |
| Unknown        | 829       | 14.48%  |
| 501-1000       | 754       | 13.17%  |
| 51-100         | 379       | 6.62%   |
| 1001-2000      | 313       | 5.47%   |
| 1-20           | 277       | 4.84%   |
| 21-50          | 208       | 3.63%   |
| 2001-3000      | 67        | 1.17%   |
| More than 3000 | 61        | 1.07%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2110      | 35.63%  |
| Unknown        | 829       | 14%     |
| 21-50          | 789       | 13.32%  |
| 101-250        | 762       | 12.87%  |
| 51-100         | 625       | 10.55%  |
| 251-500        | 418       | 7.06%   |
| 501-1000       | 249       | 4.2%    |
| 1001-2000      | 89        | 1.5%    |
| More than 3000 | 22        | 0.37%   |
| 2001-3000      | 18        | 0.3%    |
| 0              | 11        | 0.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB                      | 25        | 25     | 4.5%    |
| Seagate ST9500325AS 500GB                           | 13        | 13     | 2.34%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 11        | 13     | 1.98%   |
| Hitachi HTS543216L9SA02 160GB                       | 11        | 11     | 1.98%   |
| Toshiba MQ01ABD100 1TB                              | 10        | 11     | 1.8%    |
| Toshiba MK1653GSX 160GB                             | 9         | 9      | 1.62%   |
| Toshiba MK1655GSXF 160GB                            | 8         | 8      | 1.44%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                | 8         | 10     | 1.44%   |
| Seagate ST9500420AS 500GB                           | 8         | 8      | 1.44%   |
| Seagate ST500LM021-1KJ152 500GB                     | 7         | 7      | 1.26%   |
| Hitachi HTS545050B9A300 500GB                       | 7         | 7      | 1.26%   |
| Seagate ST1000LM035-1RK172 1TB                      | 6         | 7      | 1.08%   |
| HGST HTS725050A7E630 500GB                          | 6         | 7      | 1.08%   |
| HGST HTS541010A9E680 1TB                            | 6         | 6      | 1.08%   |
| Toshiba MQ01ABF050 500GB                            | 5         | 5      | 0.9%    |
| Seagate ST500LT012-9WS142 500GB                     | 5         | 6      | 0.9%    |
| Hitachi HTS542512K9SA00 120GB                       | 5         | 6      | 0.9%    |
| HGST HTS721010A9E630 1TB                            | 5         | 6      | 0.9%    |
| WDC WD1600BUDT-63DPZY0 160GB                        | 4         | 4      | 0.72%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 4         | 4      | 0.72%   |
| Seagate ST9320325AS 320GB                           | 4         | 4      | 0.72%   |
| Seagate ST500LM000-SSHD-8GB                         | 4         | 4      | 0.72%   |
| Seagate ST320LT007-9ZV142 320GB                     | 4         | 6      | 0.72%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 4         | 4      | 0.72%   |
| Kingston SV300S37A120G 120GB SSD                    | 4         | 4      | 0.72%   |
| Kingston SA400S37240G 240GB SSD                     | 4         | 4      | 0.72%   |
| Hitachi HTS547575A9E384 752GB                       | 4         | 4      | 0.72%   |
| HGST HTS545050A7E680 500GB                          | 4         | 4      | 0.72%   |
| Crucial CT275MX300SSD1 275GB                        | 4         | 4      | 0.72%   |
| Toshiba MQ04ABF100 1TB                              | 3         | 3      | 0.54%   |
| SK hynix HFS256G39MND-2300A 256GB SSD               | 3         | 4      | 0.54%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 3         | 3      | 0.54%   |
| Seagate ST9250315AS 250GB                           | 3         | 4      | 0.54%   |
| Seagate ST500LT012-1DG142 500GB                     | 3         | 3      | 0.54%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 3         | 3      | 0.54%   |
| Samsung Electronics SSD 870 EVO 500GB               | 3         | 3      | 0.54%   |
| Kingston SA400S37120G 120GB SSD                     | 3         | 4      | 0.54%   |
| Hitachi HTS547550A9E384 500GB                       | 3         | 3      | 0.54%   |
| Hitachi HTS545050A7E380 500GB                       | 3         | 3      | 0.54%   |
| Hitachi HTS543232A7A384 320GB                       | 3         | 3      | 0.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 110       | 120    | 19.86%  |
| Hitachi             | 79        | 85     | 14.26%  |
| Toshiba             | 68        | 70     | 12.27%  |
| WDC                 | 51        | 55     | 9.21%   |
| Fujitsu             | 40        | 40     | 7.22%   |
| HGST                | 35        | 37     | 6.32%   |
| SK hynix            | 28        | 31     | 5.05%   |
| Samsung Electronics | 27        | 29     | 4.87%   |
| Kingston            | 19        | 20     | 3.43%   |
| Micron Technology   | 16        | 17     | 2.89%   |
| Intel               | 16        | 17     | 2.89%   |
| SanDisk             | 14        | 16     | 2.53%   |
| Crucial             | 11        | 12     | 1.99%   |
| A-DATA Technology   | 10        | 11     | 1.81%   |
| LITEONIT            | 3         | 4      | 0.54%   |
| LITEON              | 3         | 3      | 0.54%   |
| SSSTC               | 2         | 2      | 0.36%   |
| KingSpec            | 2         | 2      | 0.36%   |
| JMicron Technology  | 2         | 2      | 0.36%   |
| IBM/Hitachi         | 2         | 2      | 0.36%   |
| Corsair             | 2         | 2      | 0.36%   |
| Apple               | 2         | 3      | 0.36%   |
| Unknown             | 2         | 2      | 0.36%   |
| Team                | 1         | 1      | 0.18%   |
| ShiJi               | 1         | 4      | 0.18%   |
| Plextor             | 1         | 1      | 0.18%   |
| Lenovo              | 1         | 1      | 0.18%   |
| KingDian            | 1         | 1      | 0.18%   |
| IBM                 | 1         | 1      | 0.18%   |
| GOODRAM             | 1         | 1      | 0.18%   |
| GLOWAY              | 1         | 1      | 0.18%   |
| DGM                 | 1         | 1      | 0.18%   |
| China               | 1         | 1      | 0.18%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 110       | 120    | 27.57%  |
| Hitachi             | 79        | 85     | 19.8%   |
| Toshiba             | 67        | 69     | 16.79%  |
| WDC                 | 50        | 54     | 12.53%  |
| Fujitsu             | 40        | 40     | 10.03%  |
| HGST                | 35        | 37     | 8.77%   |
| Samsung Electronics | 14        | 14     | 3.51%   |
| IBM/Hitachi         | 2         | 2      | 0.5%    |
| IBM                 | 1         | 1      | 0.25%   |
| Apple               | 1         | 2      | 0.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 396       | 424    | 71.87%  |
| SSD     | 128       | 138    | 23.23%  |
| NVMe    | 26        | 32     | 4.72%   |
| Unknown | 1         | 1      | 0.18%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 11.11%  |
| Toshiba MQ04ABF100 1TB                          | 1         | 1      | 11.11%  |
| Toshiba MK6465GSX 640GB                         | 1         | 1      | 11.11%  |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 11.11%  |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 11.11%  |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 11.11%  |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 11.11%  |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 11.11%  |
| Crucial CT500P2SSD8 500GB                       | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 2      | 22.22%  |
| Seagate             | 2         | 2      | 22.22%  |
| Samsung Electronics | 2         | 2      | 22.22%  |
| WDC                 | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 2      | 11.11%  |
| Crucial             | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3745      | 5088   | 63.07%  |
| Detected | 1635      | 2485   | 27.53%  |
| Malfunc  | 548       | 595    | 9.23%   |
| Failed   | 9         | 10     | 0.15%   |
| Limited  | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3355      | 53.88%  |
| Samsung Electronics              | 639       | 10.26%  |
| AMD                              | 530       | 8.51%   |
| Nvidia                           | 385       | 6.18%   |
| SanDisk                          | 329       | 5.28%   |
| SK hynix                         | 205       | 3.29%   |
| Toshiba America Info Systems     | 112       | 1.8%    |
| Micron Technology                | 108       | 1.73%   |
| Kingston Technology Company      | 96        | 1.54%   |
| Apple                            | 86        | 1.38%   |
| KIOXIA                           | 70        | 1.12%   |
| Phison Electronics               | 53        | 0.85%   |
| ADATA Technology                 | 50        | 0.8%    |
| Micron/Crucial Technology        | 43        | 0.69%   |
| Silicon Motion                   | 40        | 0.64%   |
| Solid State Storage Technology   | 27        | 0.43%   |
| Union Memory (Shenzhen)          | 18        | 0.29%   |
| Silicon Integrated Systems [SiS] | 13        | 0.21%   |
| Realtek Semiconductor            | 10        | 0.16%   |
| Lite-On Technology               | 7         | 0.11%   |
| MAXIO Technology (Hangzhou)      | 6         | 0.1%    |
| Yangtze Memory Technologies      | 5         | 0.08%   |
| Shenzhen Longsys Electronics     | 5         | 0.08%   |
| Lenovo                           | 5         | 0.08%   |
| Seagate Technology               | 4         | 0.06%   |
| VIA Technologies                 | 3         | 0.05%   |
| ULi Electronics                  | 3         | 0.05%   |
| Silicon Image                    | 3         | 0.05%   |
| Marvell Technology Group         | 3         | 0.05%   |
| Jiangsu Huacun Elec.             | 3         | 0.05%   |
| Biwin Storage Technology         | 3         | 0.05%   |
| INNOGRIT                         | 2         | 0.03%   |
| ASMedia Technology               | 2         | 0.03%   |
| Transcend                        | 1         | 0.02%   |
| JMicron Technology               | 1         | 0.02%   |
| Adaptec                          | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 459       | 6.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 434       | 6.51%   |
| Nvidia MCP79 AHCI Controller                                                   | 365       | 5.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 360       | 5.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 256       | 3.84%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 244       | 3.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 236       | 3.54%   |
| Intel Volume Management Device NVMe RAID Controller                            | 179       | 2.68%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 169       | 2.53%   |
| Samsung NVMe SSD Controller 980                                                | 149       | 2.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 135       | 2.02%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 131       | 1.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 119       | 1.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 102       | 1.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 101       | 1.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 96        | 1.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 96        | 1.44%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 93        | 1.39%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 92        | 1.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 92        | 1.38%   |
| Intel Tiger Lake-LP SATA Controller                                            | 88        | 1.32%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 86        | 1.29%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 84        | 1.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 83        | 1.24%   |
| Intel Comet Lake SATA AHCI Controller                                          | 81        | 1.21%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 78        | 1.17%   |
| Apple S1X NVMe Controller                                                      | 78        | 1.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 68        | 1.02%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 67        | 1%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 65        | 0.97%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 61        | 0.91%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 57        | 0.85%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 52        | 0.78%   |
| Intel SSD 660P Series                                                          | 52        | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 51        | 0.76%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 48        | 0.72%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 47        | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 43        | 0.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 41        | 0.61%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 41        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3759      | 58.09%  |
| NVMe | 1854      | 28.65%  |
| RAID | 434       | 6.71%   |
| IDE  | 423       | 6.54%   |
| SCSI | 1         | 0.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 4692      | 84.91%  |
| AMD          | 814       | 14.73%  |
| ARM          | 13        | 0.24%   |
| CentaurHauls | 5         | 0.09%   |
| Unknown      | 2         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 357       | 6.45%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 148       | 2.68%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 114       | 2.06%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 98        | 1.77%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 85        | 1.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 77        | 1.39%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 77        | 1.39%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 77        | 1.39%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 77        | 1.39%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 68        | 1.23%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 67        | 1.21%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 65        | 1.17%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 63        | 1.14%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 62        | 1.12%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 56        | 1.01%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 55        | 0.99%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 53        | 0.96%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 52        | 0.94%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 50        | 0.9%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 50        | 0.9%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 48        | 0.87%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 48        | 0.87%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 44        | 0.8%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 42        | 0.76%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 39        | 0.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 38        | 0.69%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 37        | 0.67%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 34        | 0.61%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 33        | 0.6%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 33        | 0.6%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 33        | 0.6%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 32        | 0.58%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 32        | 0.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 31        | 0.56%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 29        | 0.52%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 28        | 0.51%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 28        | 0.51%   |
| Intel 12th Gen Core i7-12700H                 | 28        | 0.51%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 27        | 0.49%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 27        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1325      | 23.96%  |
| Intel Core i7           | 1038      | 18.77%  |
| Intel Core 2 Duo        | 575       | 10.4%   |
| Other                   | 521       | 9.42%   |
| Intel Celeron           | 387       | 7%      |
| Intel Core i3           | 365       | 6.6%    |
| AMD Ryzen 5             | 235       | 4.25%   |
| Intel Atom              | 154       | 2.78%   |
| AMD Ryzen 7             | 152       | 2.75%   |
| Intel Pentium           | 103       | 1.86%   |
| Intel Core 2            | 73        | 1.32%   |
| AMD Ryzen 7 PRO         | 55        | 0.99%   |
| AMD A6                  | 42        | 0.76%   |
| Intel Pentium Dual-Core | 36        | 0.65%   |
| Intel Pentium M         | 35        | 0.63%   |
| AMD A4                  | 29        | 0.52%   |
| Intel Genuine           | 28        | 0.51%   |
| AMD Ryzen 5 PRO         | 26        | 0.47%   |
| AMD Ryzen 3             | 26        | 0.47%   |
| AMD Ryzen 9             | 24        | 0.43%   |
| AMD A8                  | 23        | 0.42%   |
| Intel Pentium Dual      | 22        | 0.4%    |
| AMD E1                  | 19        | 0.34%   |
| AMD E                   | 19        | 0.34%   |
| AMD A10                 | 16        | 0.29%   |
| AMD E2                  | 15        | 0.27%   |
| Intel Celeron M         | 14        | 0.25%   |
| Intel Pentium Silver    | 13        | 0.24%   |
| Intel Core i9           | 11        | 0.2%    |
| Intel Pentium 4         | 9         | 0.16%   |
| Intel Core m3           | 8         | 0.14%   |
| AMD Turion 64 X2 Mobile | 8         | 0.14%   |
| AMD Athlon              | 8         | 0.14%   |
| Intel Xeon              | 7         | 0.13%   |
| AMD A12                 | 7         | 0.13%   |
| AMD C-60                | 6         | 0.11%   |
| AMD C-50                | 6         | 0.11%   |
| AMD Athlon II           | 6         | 0.11%   |
| Intel Core m7           | 5         | 0.09%   |
| Intel Celeron Dual-Core | 5         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2992      | 54.1%   |
| 4      | 1602      | 28.97%  |
| 6      | 323       | 5.84%   |
| 8      | 258       | 4.67%   |
| 1      | 214       | 3.87%   |
| 10     | 56        | 1.01%   |
| 14     | 44        | 0.8%    |
| 12     | 35        | 0.63%   |
| 16     | 5         | 0.09%   |
| 3      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5524      | 99.98%  |
| 2      | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3754      | 67.88%  |
| 1      | 1775      | 32.1%   |
| 4      | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5323      | 96.31%  |
| 32-bit         | 130       | 2.35%   |
| Unknown        | 72        | 1.3%    |
| 64-bit         | 2         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1273      | 22.49%  |
| 0x1067a    | 471       | 8.32%   |
| 0x306d4    | 271       | 4.79%   |
| 0x306a9    | 252       | 4.45%   |
| 0x206a7    | 239       | 4.22%   |
| 0x806c1    | 217       | 3.83%   |
| 0x806ec    | 211       | 3.73%   |
| 0x806e9    | 153       | 2.7%    |
| 0x806ea    | 146       | 2.58%   |
| 0x40651    | 142       | 2.51%   |
| 0x406e3    | 138       | 2.44%   |
| 0x30678    | 128       | 2.26%   |
| 0x306c3    | 96        | 1.7%    |
| 0x906ea    | 84        | 1.48%   |
| 0x20655    | 81        | 1.43%   |
| 0xa0652    | 77        | 1.36%   |
| 0x406c4    | 74        | 1.31%   |
| 0x0a50000c | 74        | 1.31%   |
| 0x08108109 | 69        | 1.22%   |
| 0x6f6      | 68        | 1.2%    |
| 0x08608103 | 60        | 1.06%   |
| 0x08600106 | 59        | 1.04%   |
| 0x906a3    | 58        | 1.02%   |
| 0x706e5    | 51        | 0.9%    |
| 0x10676    | 51        | 0.9%    |
| 0x906eb    | 48        | 0.85%   |
| 0x706a8    | 48        | 0.85%   |
| 0x08108102 | 48        | 0.85%   |
| 0x906a4    | 46        | 0.81%   |
| 0x6fd      | 46        | 0.81%   |
| 0x806eb    | 42        | 0.74%   |
| 0x106ca    | 41        | 0.72%   |
| 0x506e3    | 40        | 0.71%   |
| 0x106c2    | 38        | 0.67%   |
| 0x06006705 | 38        | 0.67%   |
| 0x906e9    | 37        | 0.65%   |
| 0x506c9    | 35        | 0.62%   |
| 0x0600611a | 31        | 0.55%   |
| 0x6d8      | 30        | 0.53%   |
| 0x20652    | 28        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 995       | 17.98%  |
| Penryn           | 566       | 10.23%  |
| IvyBridge        | 345       | 6.23%   |
| SandyBridge      | 329       | 5.95%   |
| Haswell          | 328       | 5.93%   |
| Broadwell        | 311       | 5.62%   |
| TigerLake        | 275       | 4.97%   |
| Silvermont       | 265       | 4.79%   |
| Skylake          | 261       | 4.72%   |
| Unknown          | 186       | 3.36%   |
| Core             | 168       | 3.04%   |
| Westmere         | 151       | 2.73%   |
| Zen+             | 145       | 2.62%   |
| Zen 3            | 126       | 2.28%   |
| Zen 2            | 120       | 2.17%   |
| CometLake        | 110       | 1.99%   |
| Alderlake Hybrid | 104       | 1.88%   |
| Bonnell          | 98        | 1.77%   |
| Excavator        | 95        | 1.72%   |
| IceLake          | 86        | 1.55%   |
| Goldmont plus    | 81        | 1.46%   |
| P6               | 74        | 1.34%   |
| Goldmont         | 47        | 0.85%   |
| Bobcat           | 47        | 0.85%   |
| Zen              | 37        | 0.67%   |
| Puma             | 30        | 0.54%   |
| Jaguar           | 25        | 0.45%   |
| K8 Hammer        | 20        | 0.36%   |
| Tremont          | 17        | 0.31%   |
| Piledriver       | 17        | 0.31%   |
| K10 Llano        | 17        | 0.31%   |
| NetBurst         | 14        | 0.25%   |
| Nehalem          | 14        | 0.25%   |
| K10              | 13        | 0.23%   |
| K8 & K10 hybrid  | 10        | 0.18%   |
| Steamroller      | 7         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4021      | 60.2%   |
| Nvidia                           | 1540      | 23.06%  |
| AMD                              | 1101      | 16.48%  |
| Silicon Integrated Systems [SiS] | 8         | 0.12%   |
| Zhaoxin                          | 4         | 0.06%   |
| VIA Technologies                 | 2         | 0.03%   |
| S3 Graphics                      | 2         | 0.03%   |
| Neomagic                         | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 355       | 5.1%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 319       | 4.58%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 296       | 4.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 243       | 3.49%   |
| Intel UHD Graphics 620                                                                   | 217       | 3.12%   |
| Intel HD Graphics 620                                                                    | 187       | 2.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 185       | 2.66%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 184       | 2.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 164       | 2.36%   |
| Intel HD Graphics 6000                                                                   | 157       | 2.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 153       | 2.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 151       | 2.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 147       | 2.11%   |
| Intel HD Graphics 5500                                                                   | 138       | 1.98%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 123       | 1.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 117       | 1.68%   |
| Intel Core Processor Integrated Graphics Controller                                      | 116       | 1.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 116       | 1.67%   |
| AMD Renoir                                                                               | 116       | 1.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 111       | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 111       | 1.59%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 101       | 1.45%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 87        | 1.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 84        | 1.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 84        | 1.21%   |
| AMD Lucienne                                                                             | 84        | 1.21%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 83        | 1.19%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 74        | 1.06%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 62        | 0.89%   |
| Intel HD Graphics 630                                                                    | 53        | 0.76%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 53        | 0.76%   |
| Intel HD Graphics 530                                                                    | 51        | 0.73%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 50        | 0.72%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 49        | 0.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 48        | 0.69%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 45        | 0.65%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 45        | 0.65%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 43        | 0.62%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 41        | 0.59%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 40        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2927      | 52.86%  |
| Intel + Nvidia     | 892       | 16.11%  |
| 1 x AMD            | 771       | 13.92%  |
| 1 x Nvidia         | 554       | 10.01%  |
| Intel + AMD        | 175       | 3.16%   |
| AMD + Nvidia       | 92        | 1.66%   |
| 2 x AMD            | 63        | 1.14%   |
| Other              | 26        | 0.47%   |
| 2 x Intel          | 16        | 0.29%   |
| 1 x SiS            | 8         | 0.14%   |
| 1 x Zhaoxin        | 4         | 0.07%   |
| 2 x Nvidia         | 2         | 0.04%   |
| 1 x VIA            | 2         | 0.04%   |
| 1 x S3 Graphics    | 2         | 0.04%   |
| Intel + 2 x Nvidia | 2         | 0.04%   |
| 1 x Neomagic       | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 4821      | 86.52%  |
| Proprietary | 406       | 7.29%   |
| Unknown     | 345       | 6.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 4048      | 72.32%  |
| 0.01-0.5       | 806       | 14.4%   |
| 1.01-2.0       | 314       | 5.61%   |
| 3.01-4.0       | 174       | 3.11%   |
| 0.51-1.0       | 169       | 3.02%   |
| 5.01-6.0       | 38        | 0.68%   |
| 7.01-8.0       | 32        | 0.57%   |
| 2.01-3.0       | 11        | 0.2%    |
| 8.01-16.0      | 2         | 0.04%   |
| More than 64.0 | 1         | 0.02%   |
| 16.01-24.0     | 1         | 0.02%   |
| 0              | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1083      | 18.08%  |
| BOE                     | 784       | 13.09%  |
| LG Display              | 715       | 11.93%  |
| Chimei Innolux          | 685       | 11.43%  |
| Apple                   | 664       | 11.08%  |
| Samsung Electronics     | 496       | 8.28%   |
| Dell                    | 162       | 2.7%    |
| Lenovo                  | 148       | 2.47%   |
| Sharp                   | 129       | 2.15%   |
| Goldstar                | 112       | 1.87%   |
| Chi Mei Optoelectronics | 98        | 1.64%   |
| InfoVision              | 87        | 1.45%   |
| Hewlett-Packard         | 73        | 1.22%   |
| PANDA                   | 72        | 1.2%    |
| BenQ                    | 59        | 0.98%   |
| Philips                 | 57        | 0.95%   |
| AOC                     | 46        | 0.77%   |
| CSO                     | 40        | 0.67%   |
| LG Philips              | 39        | 0.65%   |
| Acer                    | 38        | 0.63%   |
| Iiyama                  | 37        | 0.62%   |
| HannStar                | 36        | 0.6%    |
| Ancor Communications    | 34        | 0.57%   |
| Unknown                 | 25        | 0.42%   |
| ViewSonic               | 22        | 0.37%   |
| Sony                    | 19        | 0.32%   |
| CPT                     | 17        | 0.28%   |
| Eizo                    | 14        | 0.23%   |
| ASUSTek Computer        | 14        | 0.23%   |
| Quanta Display          | 10        | 0.17%   |
| Panasonic               | 9         | 0.15%   |
| NEC Computers           | 8         | 0.13%   |
| MSI                     | 8         | 0.13%   |
| Pixio                   | 6         | 0.1%    |
| LGD                     | 6         | 0.1%    |
| InnoLux Display         | 6         | 0.1%    |
| Toshiba                 | 5         | 0.08%   |
| TMX                     | 4         | 0.07%   |
| Fujitsu Siemens         | 4         | 0.07%   |
| AGO                     | 4         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                 | 210       | 3.47%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 191       | 3.15%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                 | 54        | 0.89%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 47        | 0.78%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 46        | 0.76%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 45        | 0.74%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 45        | 0.74%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 42        | 0.69%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                 | 38        | 0.63%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 29        | 0.48%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                 | 29        | 0.48%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 29        | 0.48%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 29        | 0.48%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 28        | 0.46%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 26        | 0.43%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 25        | 0.41%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 25        | 0.41%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 24        | 0.4%    |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                 | 22        | 0.36%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 21        | 0.35%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 20        | 0.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 19        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 19        | 0.31%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 19        | 0.31%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 19        | 0.31%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 18        | 0.3%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 18        | 0.3%    |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 17        | 0.28%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 17        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 16        | 0.26%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 16        | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 15        | 0.25%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch        | 15        | 0.25%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 15        | 0.25%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch       | 15        | 0.25%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 14        | 0.23%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 14        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 14        | 0.23%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 14        | 0.23%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch     | 14        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2208      | 39.06%  |
| 1366x768 (WXGA)    | 1520      | 26.89%  |
| 1280x800 (WXGA)    | 602       | 10.65%  |
| 1600x900 (HD+)     | 235       | 4.16%   |
| 3840x2160 (4K)     | 167       | 2.95%   |
| 1440x900 (WXGA+)   | 157       | 2.78%   |
| 1920x1200 (WUXGA)  | 135       | 2.39%   |
| 2560x1440 (QHD)    | 129       | 2.28%   |
| 1024x600           | 75        | 1.33%   |
| 2560x1600          | 46        | 0.81%   |
| 1280x1024 (SXGA)   | 43        | 0.76%   |
| 1680x1050 (WSXGA+) | 39        | 0.69%   |
| 2560x1080          | 31        | 0.55%   |
| 3840x2400          | 30        | 0.53%   |
| 3440x1440          | 25        | 0.44%   |
| 2880x1800          | 24        | 0.42%   |
| 1360x768           | 22        | 0.39%   |
| 2288x1287          | 21        | 0.37%   |
| 1024x768 (XGA)     | 21        | 0.37%   |
| 3200x1800 (QHD+)   | 11        | 0.19%   |
| Unknown            | 10        | 0.18%   |
| 2160x1440          | 9         | 0.16%   |
| 2256x1504          | 8         | 0.14%   |
| 1600x1200          | 8         | 0.14%   |
| 3840x1080          | 7         | 0.12%   |
| 1400x1050          | 6         | 0.11%   |
| 3072x1920          | 5         | 0.09%   |
| 1920x540           | 5         | 0.09%   |
| 1280x720 (HD)      | 5         | 0.09%   |
| 3456x2160          | 4         | 0.07%   |
| 1024x576           | 4         | 0.07%   |
| 800x1280           | 3         | 0.05%   |
| 3840x1200          | 3         | 0.05%   |
| 3840x1100          | 3         | 0.05%   |
| 2880x1920          | 3         | 0.05%   |
| 2304x1440          | 3         | 0.05%   |
| 2240x1400          | 3         | 0.05%   |
| 1920x1280          | 3         | 0.05%   |
| 3200x2000          | 2         | 0.04%   |
| 3000x2000          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1888      | 31.51%  |
| 13      | 1298      | 21.66%  |
| 14      | 781       | 13.03%  |
| 17      | 331       | 5.52%   |
| 11      | 307       | 5.12%   |
| 24      | 213       | 3.55%   |
| 12      | 211       | 3.52%   |
| 27      | 165       | 2.75%   |
| 23      | 137       | 2.29%   |
| 21      | 116       | 1.94%   |
| 10      | 76        | 1.27%   |
| 16      | 55        | 0.92%   |
| Unknown | 51        | 0.85%   |
| 18      | 50        | 0.83%   |
| 34      | 47        | 0.78%   |
| 19      | 37        | 0.62%   |
| 31      | 35        | 0.58%   |
| 22      | 22        | 0.37%   |
| 142     | 21        | 0.35%   |
| 25      | 17        | 0.28%   |
| 20      | 16        | 0.27%   |
| 72      | 12        | 0.2%    |
| 32      | 12        | 0.2%    |
| 40      | 11        | 0.18%   |
| 54      | 10        | 0.17%   |
| 8       | 10        | 0.17%   |
| 84      | 8         | 0.13%   |
| 29      | 8         | 0.13%   |
| 28      | 7         | 0.12%   |
| 46      | 5         | 0.08%   |
| 26      | 5         | 0.08%   |
| 49      | 4         | 0.07%   |
| 48      | 4         | 0.07%   |
| 52      | 3         | 0.05%   |
| 43      | 3         | 0.05%   |
| 33      | 3         | 0.05%   |
| 7       | 2         | 0.03%   |
| 86      | 1         | 0.02%   |
| 65      | 1         | 0.02%   |
| 58      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 3118      | 52.5%   |
| 201-300        | 1440      | 24.25%  |
| 501-600        | 486       | 8.18%   |
| 351-400        | 388       | 6.53%   |
| 401-500        | 218       | 3.67%   |
| 601-700        | 73        | 1.23%   |
| 701-800        | 62        | 1.04%   |
| Unknown        | 51        | 0.86%   |
| 1001-1500      | 33        | 0.56%   |
| More than 2000 | 21        | 0.35%   |
| 1501-2000      | 20        | 0.34%   |
| 801-900        | 13        | 0.22%   |
| 101-200        | 11        | 0.19%   |
| 1-100          | 3         | 0.05%   |
| 901-1000       | 2         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 4055      | 75.79%  |
| 16/10   | 1045      | 19.53%  |
| 21/9    | 51        | 0.95%   |
| 5/4     | 43        | 0.8%    |
| 4/3     | 40        | 0.75%   |
| 3/2     | 39        | 0.73%   |
| Unknown | 33        | 0.62%   |
| 1.00    | 21        | 0.39%   |
| 32/9    | 5         | 0.09%   |
| 2.65    | 5         | 0.09%   |
| 3.40    | 3         | 0.06%   |
| 3.20    | 3         | 0.06%   |
| 0.67    | 2         | 0.04%   |
| 6/5     | 1         | 0.02%   |
| 3.73    | 1         | 0.02%   |
| 1.96    | 1         | 0.02%   |
| 0.58    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1880      | 31.46%  |
| 81-90          | 1732      | 28.99%  |
| 201-250        | 375       | 6.28%   |
| 71-80          | 338       | 5.66%   |
| 51-60          | 310       | 5.19%   |
| 121-130        | 263       | 4.4%    |
| 61-70          | 205       | 3.43%   |
| 301-350        | 169       | 2.83%   |
| 351-500        | 105       | 1.76%   |
| 251-300        | 93        | 1.56%   |
| 151-200        | 86        | 1.44%   |
| 41-50          | 76        | 1.27%   |
| 141-150        | 69        | 1.15%   |
| More than 1000 | 61        | 1.02%   |
| 111-120        | 53        | 0.89%   |
| Unknown        | 51        | 0.85%   |
| 131-140        | 44        | 0.74%   |
| 501-1000       | 28        | 0.47%   |
| 91-100         | 23        | 0.38%   |
| 1-40           | 14        | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2471      | 42.17%  |
| 101-120       | 1907      | 32.55%  |
| 51-100        | 834       | 14.23%  |
| 161-240       | 398       | 6.79%   |
| More than 240 | 127       | 2.17%   |
| 1-50          | 71        | 1.21%   |
| Unknown       | 51        | 0.87%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 4391      | 77.73%  |
| 2     | 829       | 14.68%  |
| 0     | 338       | 5.98%   |
| 3     | 88        | 1.56%   |
| 4     | 2         | 0.04%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2794      | 31.45%  |
| Realtek Semiconductor             | 2475      | 27.86%  |
| Qualcomm Atheros                  | 1130      | 12.72%  |
| Broadcom                          | 802       | 9.03%   |
| Nvidia                            | 379       | 4.27%   |
| Broadcom Limited                  | 274       | 3.08%   |
| Marvell Technology Group          | 155       | 1.74%   |
| MediaTek                          | 121       | 1.36%   |
| ASIX Electronics                  | 69        | 0.78%   |
| Ralink                            | 65        | 0.73%   |
| TP-Link                           | 49        | 0.55%   |
| Dell                              | 42        | 0.47%   |
| Sierra Wireless                   | 41        | 0.46%   |
| Samsung Electronics               | 37        | 0.42%   |
| Qualcomm                          | 37        | 0.42%   |
| Lenovo                            | 36        | 0.41%   |
| Ralink Technology                 | 34        | 0.38%   |
| JMicron Technology                | 32        | 0.36%   |
| Xiaomi                            | 29        | 0.33%   |
| Ericsson Business Mobile Networks | 29        | 0.33%   |
| DisplayLink                       | 22        | 0.25%   |
| Hewlett-Packard                   | 19        | 0.21%   |
| Huawei Technologies               | 18        | 0.2%    |
| Fibocom                           | 14        | 0.16%   |
| Silicon Integrated Systems [SiS]  | 12        | 0.14%   |
| Qualcomm Atheros Communications   | 9         | 0.1%    |
| OPPO Electronics                  | 9         | 0.1%    |
| NetGear                           | 9         | 0.1%    |
| Cypress Semiconductor             | 9         | 0.1%    |
| ASUSTek Computer                  | 8         | 0.09%   |
| Microchip Technology              | 7         | 0.08%   |
| Attansic Technology               | 7         | 0.08%   |
| Motorola PCS                      | 6         | 0.07%   |
| ICS Advent                        | 6         | 0.07%   |
| Apple                             | 6         | 0.07%   |
| U-Blox                            | 5         | 0.06%   |
| Google                            | 5         | 0.06%   |
| Edimax Technology                 | 5         | 0.06%   |
| D-Link                            | 5         | 0.06%   |
| AMD                               | 5         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 1490      | 14.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 415       | 3.9%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 369       | 3.47%   |
| Nvidia MCP79 Ethernet                                                                 | 366       | 3.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 242       | 2.28%   |
| Intel Wireless 8265 / 8275                                                            | 234       | 2.2%    |
| Intel Wireless 7260                                                                   | 233       | 2.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 229       | 2.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 212       | 1.99%   |
| Intel Wi-Fi 6 AX200                                                                   | 195       | 1.83%   |
| Intel Wireless 7265                                                                   | 193       | 1.82%   |
| Intel Wi-Fi 6 AX201                                                                   | 191       | 1.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 166       | 1.56%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 164       | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 152       | 1.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 139       | 1.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 137       | 1.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 133       | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 132       | 1.24%   |
| Intel Wireless 8260                                                                   | 129       | 1.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 125       | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 116       | 1.09%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 106       | 1%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 102       | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 97        | 0.91%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 89        | 0.84%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 85        | 0.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 83        | 0.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 83        | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 82        | 0.77%   |
| Intel Ethernet Connection I219-LM                                                     | 74        | 0.7%    |
| Intel Wireless 3165                                                                   | 69        | 0.65%   |
| Intel Ethernet Connection I218-LM                                                     | 67        | 0.63%   |
| Intel Ethernet Connection (4) I219-V                                                  | 67        | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 65        | 0.61%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 60        | 0.56%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 59        | 0.55%   |
| ASIX AX88179 Gigabit Ethernet                                                         | 58        | 0.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 56        | 0.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 56        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2636      | 46.61%  |
| Qualcomm Atheros                      | 1004      | 17.75%  |
| Realtek Semiconductor                 | 708       | 12.52%  |
| Broadcom                              | 677       | 11.97%  |
| Broadcom Limited                      | 227       | 4.01%   |
| MediaTek                              | 113       | 2%      |
| Ralink                                | 65        | 1.15%   |
| Sierra Wireless                       | 41        | 0.73%   |
| Ralink Technology                     | 34        | 0.6%    |
| TP-Link                               | 29        | 0.51%   |
| Dell                                  | 27        | 0.48%   |
| Qualcomm                              | 21        | 0.37%   |
| Fibocom                               | 14        | 0.25%   |
| Qualcomm Atheros Communications       | 9         | 0.16%   |
| NetGear                               | 9         | 0.16%   |
| ASUSTek Computer                      | 8         | 0.14%   |
| Edimax Technology                     | 5         | 0.09%   |
| Hewlett-Packard                       | 4         | 0.07%   |
| Microsoft                             | 3         | 0.05%   |
| D-Link System                         | 3         | 0.05%   |
| D-Link                                | 3         | 0.05%   |
| Wilocity                              | 2         | 0.04%   |
| Quectel Wireless Solutions            | 2         | 0.04%   |
| Belkin Components                     | 2         | 0.04%   |
| 3Com                                  | 2         | 0.04%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| Z-Com                                 | 1         | 0.02%   |
| Winbond Electronics                   | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| Marvell Technology Group              | 1         | 0.02%   |
| Cinterion                             | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 369       | 6.49%   |
| Intel Wireless 8265 / 8275                                                            | 234       | 4.11%   |
| Intel Wireless 7260                                                                   | 233       | 4.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 229       | 4.03%   |
| Intel Wi-Fi 6 AX200                                                                   | 195       | 3.43%   |
| Intel Wireless 7265                                                                   | 193       | 3.39%   |
| Intel Wi-Fi 6 AX201                                                                   | 191       | 3.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 166       | 2.92%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 164       | 2.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 152       | 2.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 139       | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 137       | 2.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 133       | 2.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 132       | 2.32%   |
| Intel Wireless 8260                                                                   | 129       | 2.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 125       | 2.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 116       | 2.04%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 106       | 1.86%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 102       | 1.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 97        | 1.71%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 85        | 1.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 83        | 1.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 83        | 1.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 82        | 1.44%   |
| Intel Wireless 3165                                                                   | 69        | 1.21%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 60        | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 56        | 0.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 56        | 0.98%   |
| Intel Wireless-AC 9260                                                                | 55        | 0.97%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 52        | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 51        | 0.9%    |
| Broadcom BCM43142 802.11b/g/n                                                         | 49        | 0.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 46        | 0.81%   |
| Intel Centrino Ultimate-N 6300                                                        | 46        | 0.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 45        | 0.79%   |
| Intel Wireless 3160                                                                   | 43        | 0.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 38        | 0.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 37        | 0.65%   |
| Intel Centrino Advanced-N 6200                                                        | 37        | 0.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 35        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2210      | 46.6%   |
| Intel                            | 1143      | 24.1%   |
| Nvidia                           | 379       | 7.99%   |
| Qualcomm Atheros                 | 256       | 5.4%    |
| Broadcom                         | 171       | 3.61%   |
| Marvell Technology Group         | 154       | 3.25%   |
| ASIX Electronics                 | 69        | 1.46%   |
| Broadcom Limited                 | 50        | 1.05%   |
| Samsung Electronics              | 37        | 0.78%   |
| Lenovo                           | 36        | 0.76%   |
| JMicron Technology               | 32        | 0.67%   |
| Xiaomi                           | 29        | 0.61%   |
| DisplayLink                      | 22        | 0.46%   |
| TP-Link                          | 20        | 0.42%   |
| Qualcomm                         | 15        | 0.32%   |
| Silicon Integrated Systems [SiS] | 12        | 0.25%   |
| Huawei Technologies              | 12        | 0.25%   |
| OPPO Electronics                 | 9         | 0.19%   |
| Cypress Semiconductor            | 9         | 0.19%   |
| MediaTek                         | 8         | 0.17%   |
| Microchip Technology             | 7         | 0.15%   |
| Hewlett-Packard                  | 7         | 0.15%   |
| Attansic Technology              | 7         | 0.15%   |
| ICS Advent                       | 6         | 0.13%   |
| Apple                            | 6         | 0.13%   |
| Motorola PCS                     | 5         | 0.11%   |
| Google                           | 5         | 0.11%   |
| Spreadtrum Communications        | 4         | 0.08%   |
| VIA Technologies                 | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.04%   |
| National Semiconductor           | 2         | 0.04%   |
| LG Electronics                   | 2         | 0.04%   |
| D-Link                           | 2         | 0.04%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.02%   |
| ULi Electronics                  | 1         | 0.02%   |
| MosChip Semiconductor            | 1         | 0.02%   |
| Linksys                          | 1         | 0.02%   |
| LeEco                            | 1         | 0.02%   |
| HTC (High Tech Computer)         | 1         | 0.02%   |
| HMD Global                       | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1490      | 31.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 415       | 8.64%   |
| Nvidia MCP79 Ethernet                                             | 366       | 7.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 242       | 5.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 212       | 4.42%   |
| Intel Ethernet Connection (4) I219-LM                             | 89        | 1.85%   |
| Intel Ethernet Connection I219-LM                                 | 74        | 1.54%   |
| Intel Ethernet Connection I218-LM                                 | 67        | 1.4%    |
| Intel Ethernet Connection (4) I219-V                              | 67        | 1.4%    |
| Intel Ethernet Connection (3) I218-LM                             | 65        | 1.35%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 59        | 1.23%   |
| ASIX AX88179 Gigabit Ethernet                                     | 58        | 1.21%   |
| Intel 82577LM Gigabit Network Connection                          | 51        | 1.06%   |
| Intel 82567LM Gigabit Network Connection                          | 42        | 0.87%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 41        | 0.85%   |
| Intel Ethernet Connection (6) I219-V                              | 41        | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 40        | 0.83%   |
| Intel Ethernet Connection I217-LM                                 | 39        | 0.81%   |
| Intel Ethernet Connection I219-V                                  | 36        | 0.75%   |
| Intel Ethernet Connection (13) I219-V                             | 36        | 0.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 35        | 0.73%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 33        | 0.69%   |
| Intel Ethernet Connection (10) I219-V                             | 28        | 0.58%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 27        | 0.56%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 25        | 0.52%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 24        | 0.5%    |
| Intel 82579V Gigabit Network Connection                           | 24        | 0.5%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 23        | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 22        | 0.46%   |
| Intel Ethernet Connection (6) I219-LM                             | 22        | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 21        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 21        | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 21        | 0.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 20        | 0.42%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 20        | 0.42%   |
| Intel Ethernet Connection (16) I219-V                             | 20        | 0.42%   |
| Intel Ethernet Connection (13) I219-LM                            | 18        | 0.37%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 17        | 0.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 17        | 0.35%   |
| Realtek RTL8125 2.5GbE Controller                                 | 16        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5413      | 53.83%  |
| Ethernet | 4501      | 44.76%  |
| Modem    | 134       | 1.33%   |
| Unknown  | 8         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4164      | 71.23%  |
| Ethernet | 1681      | 28.75%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 4045      | 73.09%  |
| 1     | 1353      | 24.45%  |
| 0     | 83        | 1.5%    |
| 3     | 51        | 0.92%   |
| 5     | 1         | 0.02%   |
| 4     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4577      | 81.63%  |
| Yes  | 1030      | 18.37%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2013      | 44.84%  |
| Apple                           | 648       | 14.44%  |
| Realtek Semiconductor           | 421       | 9.38%   |
| Qualcomm Atheros Communications | 382       | 8.51%   |
| Broadcom                        | 213       | 4.74%   |
| IMC Networks                    | 177       | 3.94%   |
| Lite-On Technology              | 168       | 3.74%   |
| Foxconn / Hon Hai               | 129       | 2.87%   |
| Dell                            | 68        | 1.51%   |
| Hewlett-Packard                 | 52        | 1.16%   |
| Cambridge Silicon Radio         | 49        | 1.09%   |
| Toshiba                         | 32        | 0.71%   |
| ASUSTek Computer                | 30        | 0.67%   |
| Realtek                         | 29        | 0.65%   |
| Ralink                          | 20        | 0.45%   |
| Foxconn International           | 10        | 0.22%   |
| Ralink Technology               | 8         | 0.18%   |
| Alps Electric                   | 8         | 0.18%   |
| MediaTek                        | 5         | 0.11%   |
| USI                             | 4         | 0.09%   |
| Fujitsu                         | 4         | 0.09%   |
| Taiyo Yuden                     | 3         | 0.07%   |
| Micro Star International        | 2         | 0.04%   |
| Chicony Electronics             | 2         | 0.04%   |
| Askey Computer                  | 2         | 0.04%   |
| Unknown                         | 1         | 0.02%   |
| TP-Link                         | 1         | 0.02%   |
| Smart Modular Technologies      | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Opticis                         | 1         | 0.02%   |
| Marvell Semiconductor           | 1         | 0.02%   |
| Edimax Technology               | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |
| Belkin Components               | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 846       | 18.83%  |
| Intel AX201 Bluetooth                               | 377       | 8.39%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 352       | 7.83%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 313       | 6.96%   |
| Realtek Bluetooth Radio                             | 281       | 6.25%   |
| Qualcomm Atheros  Bluetooth Device                  | 216       | 4.81%   |
| Intel AX200 Bluetooth                               | 186       | 4.14%   |
| Apple Bluetooth USB Host Controller                 | 165       | 3.67%   |
| Realtek  Bluetooth 4.2 Adapter                      | 90        | 2%      |
| Intel Bluetooth Device                              | 85        | 1.89%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 1.69%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 57        | 1.27%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 52        | 1.16%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 50        | 1.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 50        | 1.11%   |
| Foxconn / Hon Hai Bluetooth Device                  | 50        | 1.11%   |
| IMC Networks Bluetooth Radio                        | 49        | 1.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 49        | 1.09%   |
| Apple Bluetooth Host Controller                     | 47        | 1.05%   |
| IMC Networks Bluetooth Device                       | 45        | 1%      |
| Broadcom BCM2045B (BDC-2.1)                         | 44        | 0.98%   |
| Lite-On Bluetooth Device                            | 41        | 0.91%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 40        | 0.89%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 39        | 0.87%   |
| IMC Networks Wireless_Device                        | 39        | 0.87%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 38        | 0.85%   |
| Intel AX210 Bluetooth                               | 38        | 0.85%   |
| Intel Wireless-AC 3168 Bluetooth                    | 36        | 0.8%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 34        | 0.76%   |
| Realtek Bluetooth Radio                             | 29        | 0.65%   |
| Lite-On Wireless_Device                             | 25        | 0.56%   |
| Lite-On Atheros AR3012 Bluetooth                    | 25        | 0.56%   |
| HP Broadcom 2070 Bluetooth Combo                    | 23        | 0.51%   |
| Realtek RTL8723B Bluetooth                          | 22        | 0.49%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 22        | 0.49%   |
| Dell DW375 Bluetooth Module                         | 21        | 0.47%   |
| Dell BCM20702A0 Bluetooth Module                    | 21        | 0.47%   |
| Ralink RT3290 Bluetooth                             | 20        | 0.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 19        | 0.42%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 15        | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4234      | 65.59%  |
| Nvidia                                       | 933       | 14.45%  |
| AMD                                          | 896       | 13.88%  |
| C-Media Electronics                          | 47        | 0.73%   |
| Realtek Semiconductor                        | 36        | 0.56%   |
| Logitech                                     | 35        | 0.54%   |
| Lenovo                                       | 33        | 0.51%   |
| Texas Instruments                            | 20        | 0.31%   |
| Plantronics                                  | 19        | 0.29%   |
| GN Netcom                                    | 18        | 0.28%   |
| Hewlett-Packard                              | 15        | 0.23%   |
| Silicon Integrated Systems [SiS]             | 13        | 0.2%    |
| Generalplus Technology                       | 11        | 0.17%   |
| ASUSTek Computer                             | 10        | 0.15%   |
| Creative Technology                          | 9         | 0.14%   |
| JMTek                                        | 8         | 0.12%   |
| Zoran Co. Personal Media Division (Nogatech) | 6         | 0.09%   |
| Focusrite-Novation                           | 6         | 0.09%   |
| Kingston Technology                          | 5         | 0.08%   |
| Zhaoxin                                      | 4         | 0.06%   |
| RODE Microphones                             | 4         | 0.06%   |
| Razer USA                                    | 4         | 0.06%   |
| Dell                                         | 4         | 0.06%   |
| CMX Systems                                  | 4         | 0.06%   |
| Yamaha                                       | 3         | 0.05%   |
| VIA Technologies                             | 3         | 0.05%   |
| ULi Electronics                              | 3         | 0.05%   |
| Sennheiser Communications                    | 3         | 0.05%   |
| Microsoft                                    | 3         | 0.05%   |
| BEHRINGER International                      | 3         | 0.05%   |
| Apple                                        | 3         | 0.05%   |
| XMOS                                         | 2         | 0.03%   |
| SteelSeries ApS                              | 2         | 0.03%   |
| Sony                                         | 2         | 0.03%   |
| SAVITECH                                     | 2         | 0.03%   |
| M-Audio                                      | 2         | 0.03%   |
| Fujitsu                                      | 2         | 0.03%   |
| ESS Technology                               | 2         | 0.03%   |
| Conexant Systems                             | 2         | 0.03%   |
| Blue Microphones                             | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 638       | 8.17%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 518       | 6.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 408       | 5.22%   |
| Nvidia MCP79 High Definition Audio                                                                | 368       | 4.71%   |
| Intel Broadwell-U Audio Controller                                                                | 311       | 3.98%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 307       | 3.93%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 279       | 3.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 273       | 3.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 265       | 3.39%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 190       | 2.43%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 190       | 2.43%   |
| Intel 8 Series HD Audio Controller                                                                | 190       | 2.43%   |
| Intel Cannon Lake PCH cAVS                                                                        | 177       | 2.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 177       | 2.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 169       | 2.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 163       | 2.09%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 161       | 2.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 159       | 2.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 137       | 1.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 126       | 1.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 119       | 1.52%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 117       | 1.5%    |
| AMD FCH Azalia Controller                                                                         | 114       | 1.46%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 110       | 1.41%   |
| AMD Kabini HDMI/DP Audio                                                                          | 100       | 1.28%   |
| Intel Comet Lake PCH cAVS                                                                         | 99        | 1.27%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 91        | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 86        | 1.1%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 81        | 1.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 79        | 1.01%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 63        | 0.81%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 60        | 0.77%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 60        | 0.77%   |
| Intel CM238 HD Audio Controller                                                                   | 59        | 0.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 57        | 0.73%   |
| AMD High Definition Audio Controller                                                              | 50        | 0.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 47        | 0.6%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 45        | 0.58%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 45        | 0.58%   |
| AMD Wrestler HDMI Audio                                                                           | 38        | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 1445      | 27.36%  |
| Samsung Electronics | 1402      | 26.55%  |
| Micron Technology   | 614       | 11.63%  |
| Kingston            | 373       | 7.06%   |
| Unknown             | 355       | 6.72%   |
| Crucial             | 263       | 4.98%   |
| Elpida              | 149       | 2.82%   |
| A-DATA Technology   | 109       | 2.06%   |
| Ramaxel Technology  | 99        | 1.87%   |
| Corsair             | 56        | 1.06%   |
| Nanya Technology    | 55        | 1.04%   |
| Smart               | 43        | 0.81%   |
| Unknown (ABCD)      | 40        | 0.76%   |
| GOODRAM             | 26        | 0.49%   |
| G.Skill             | 26        | 0.49%   |
| Unknown             | 23        | 0.44%   |
| Transcend           | 22        | 0.42%   |
| Team                | 18        | 0.34%   |
| Teikon              | 10        | 0.19%   |
| Silicon Power       | 9         | 0.17%   |
| ASint Technology    | 9         | 0.17%   |
| Apacer              | 9         | 0.17%   |
| Patriot             | 8         | 0.15%   |
| 48spaces            | 8         | 0.15%   |
| ff                  | 7         | 0.13%   |
| 4ea5                | 7         | 0.13%   |
| Smart Brazil        | 6         | 0.11%   |
| Timetec             | 5         | 0.09%   |
| AMD                 | 5         | 0.09%   |
| Qimonda             | 4         | 0.08%   |
| PNY                 | 4         | 0.08%   |
| Neo Forza           | 4         | 0.08%   |
| Wilk                | 3         | 0.06%   |
| Kllisre             | 3         | 0.06%   |
| Infineon            | 3         | 0.06%   |
| Goldkey             | 3         | 0.06%   |
| fef5                | 3         | 0.06%   |
| CSX                 | 3         | 0.06%   |
| Avant               | 3         | 0.06%   |
| Unknown (89F7)      | 2         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 265       | 4.76%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 1.22%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 68        | 1.22%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 1.13%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 53        | 0.95%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 53        | 0.95%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 48        | 0.86%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 46        | 0.83%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 45        | 0.81%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 45        | 0.81%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 44        | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 44        | 0.79%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 44        | 0.79%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 43        | 0.77%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 41        | 0.74%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 40        | 0.72%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 38        | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 37        | 0.66%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 36        | 0.65%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 35        | 0.63%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 33        | 0.59%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 33        | 0.59%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 32        | 0.57%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 30        | 0.54%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.52%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 28        | 0.5%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 27        | 0.49%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 27        | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 26        | 0.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 26        | 0.47%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 26        | 0.47%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 25        | 0.45%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 25        | 0.45%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.45%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 24        | 0.43%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 24        | 0.43%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 24        | 0.43%   |
| Unknown                                                          | 23        | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 21        | 0.38%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 21        | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1840      | 40.36%  |
| DDR3    | 1510      | 33.12%  |
| DDR2    | 624       | 13.69%  |
| LPDDR4  | 175       | 3.84%   |
| LPDDR3  | 157       | 3.44%   |
| SDRAM   | 92        | 2.02%   |
| DDR     | 46        | 1.01%   |
| DDR5    | 38        | 0.83%   |
| LPDDR5  | 34        | 0.75%   |
| Unknown | 31        | 0.68%   |
| DRAM    | 11        | 0.24%   |
| RAM     | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 4127      | 90.23%  |
| Row Of Chips | 327       | 7.15%   |
| Unknown      | 69        | 1.51%   |
| Chip         | 33        | 0.72%   |
| DIMM         | 18        | 0.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1636      | 32.89%  |
| 4096  | 1263      | 25.39%  |
| 2048  | 734       | 14.76%  |
| 1024  | 582       | 11.7%   |
| 16384 | 563       | 11.32%  |
| 32768 | 126       | 2.53%   |
| 512   | 48        | 0.97%   |
| 256   | 17        | 0.34%   |
| 128   | 2         | 0.04%   |
| 8072  | 1         | 0.02%   |
| 1536  | 1         | 0.02%   |
| 384   | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 1131      | 23.2%   |
| 2667    | 819       | 16.8%   |
| 3200    | 797       | 16.35%  |
| 800     | 398       | 8.16%   |
| 2400    | 293       | 6.01%   |
| 2133    | 218       | 4.47%   |
| 1334    | 205       | 4.2%    |
| 667     | 192       | 3.94%   |
| 1333    | 150       | 3.08%   |
| Unknown | 118       | 2.42%   |
| 1067    | 71        | 1.46%   |
| 4267    | 68        | 1.39%   |
| 1867    | 58        | 1.19%   |
| 3266    | 45        | 0.92%   |
| 4800    | 37        | 0.76%   |
| 6400    | 35        | 0.72%   |
| 4199    | 33        | 0.68%   |
| 1066    | 33        | 0.68%   |
| 533     | 28        | 0.57%   |
| 2048    | 22        | 0.45%   |
| 975     | 22        | 0.45%   |
| 8400    | 17        | 0.35%   |
| 4266    | 15        | 0.31%   |
| 400     | 11        | 0.23%   |
| 3733    | 9         | 0.18%   |
| 333     | 9         | 0.18%   |
| 1866    | 8         | 0.16%   |
| 266     | 8         | 0.16%   |
| 5600    | 4         | 0.08%   |
| 2666    | 4         | 0.08%   |
| 2933    | 3         | 0.06%   |
| 933     | 3         | 0.06%   |
| 1776    | 2         | 0.04%   |
| 1639    | 2         | 0.04%   |
| 3000    | 1         | 0.02%   |
| 2134    | 1         | 0.02%   |
| 1596    | 1         | 0.02%   |
| 666     | 1         | 0.02%   |
| 200     | 1         | 0.02%   |
| 166     | 1         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 12        | 34.29%  |
| Canon                 | 5         | 14.29%  |
| Xerox                 | 4         | 11.43%  |
| Brother Industries    | 4         | 11.43%  |
| Samsung Electronics   | 2         | 5.71%   |
| Kyocera               | 2         | 5.71%   |
| Xiaomi                | 1         | 2.86%   |
| STMicroelectronics    | 1         | 2.86%   |
| Seiko Epson           | 1         | 2.86%   |
| Pantum                | 1         | 2.86%   |
| Lexmark International | 1         | 2.86%   |
| Dymo-CoStar           | 1         | 2.86%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Xerox B205                                                | 4         | 10.81%  |
| Xiaomi MiMouse 2                                          | 1         | 2.7%    |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 2.7%    |
| Seiko Epson L120 Series                                   | 1         | 2.7%    |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 2.7%    |
| Samsung CLX-3300 Series                                   | 1         | 2.7%    |
| Pantum P2500W series                                      | 1         | 2.7%    |
| Lexmark International E260dn                              | 1         | 2.7%    |
| Kyocera FS-1120MFP                                        | 1         | 2.7%    |
| Kyocera ECOSYS P2335d                                     | 1         | 2.7%    |
| HP OfficeJet 3830 series                                  | 1         | 2.7%    |
| HP LaserJet P1102                                         | 1         | 2.7%    |
| HP LaserJet P1005                                         | 1         | 2.7%    |
| HP LaserJet 1200                                          | 1         | 2.7%    |
| HP LaserJet 1160 series                                   | 1         | 2.7%    |
| HP LaserJet 1150                                          | 1         | 2.7%    |
| HP LaserJet 1022                                          | 1         | 2.7%    |
| HP LaserJet 1020                                          | 1         | 2.7%    |
| HP Ink Tank 110 series                                    | 1         | 2.7%    |
| HP EWS UPD                                                | 1         | 2.7%    |
| HP DeskJet 2600 series                                    | 1         | 2.7%    |
| HP Deskjet 2540 series                                    | 1         | 2.7%    |
| HP DeskJet 2130 series                                    | 1         | 2.7%    |
| Dymo-CoStar DYMO XTL                                      | 1         | 2.7%    |
| Dymo-CoStar DYMO LabelWriter 4XL                          | 1         | 2.7%    |
| Canon PIXMA MX920 Series                                  | 1         | 2.7%    |
| Canon LiDE 300                                            | 1         | 2.7%    |
| Canon LBP3010/LBP3018/LBP3050                             | 1         | 2.7%    |
| Canon LBP2900                                             | 1         | 2.7%    |
| Canon G3010 series                                        | 1         | 2.7%    |
| Brother PT-9500PC                                         | 1         | 2.7%    |
| Brother MFC-L2707DW                                       | 1         | 2.7%    |
| Brother HL-L2340D series                                  | 1         | 2.7%    |
| Brother DCP-7010                                          | 1         | 2.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Canon              | 6         | 40%     |
| Seiko Epson        | 5         | 33.33%  |
| Mustek Systems     | 2         | 13.33%  |
| Ultima Electronics | 1         | 6.67%   |
| Hewlett-Packard    | 1         | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 120                                                               | 2         | 13.33%  |
| Canon CanoScan LiDE 110                                                               | 2         | 13.33%  |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 6.67%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1         | 6.67%   |
| Seiko Epson GT-9800F [Perfection 3200]                                                | 1         | 6.67%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1         | 6.67%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 1         | 6.67%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 1         | 6.67%   |
| Mustek Systems SNAPSCAN e22                                                           | 1         | 6.67%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 1         | 6.67%   |
| HP Scanjet 200                                                                        | 1         | 6.67%   |
| Canon CanoScan LIDE 25                                                                | 1         | 6.67%   |
| Canon CanoScan LiDE 220                                                               | 1         | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1065      | 24.36%  |
| IMC Networks                           | 484       | 11.07%  |
| Microdia                               | 354       | 8.1%    |
| Realtek Semiconductor                  | 344       | 7.87%   |
| Quanta                                 | 318       | 7.27%   |
| Bison Electronics                      | 268       | 6.13%   |
| Sunplus Innovation Technology          | 245       | 5.6%    |
| Acer                                   | 161       | 3.68%   |
| Cheng Uei Precision Industry (Foxlink) | 136       | 3.11%   |
| Suyin                                  | 135       | 3.09%   |
| Lite-On Technology                     | 110       | 2.52%   |
| Syntek                                 | 99        | 2.26%   |
| Luxvisions Innotech Limited            | 97        | 2.22%   |
| Apple                                  | 79        | 1.81%   |
| Silicon Motion                         | 62        | 1.42%   |
| Logitech                               | 62        | 1.42%   |
| Alcor Micro                            | 44        | 1.01%   |
| Lenovo                                 | 39        | 0.89%   |
| Ricoh                                  | 34        | 0.78%   |
| Sonix Technology                       | 22        | 0.5%    |
| Z-Star Microelectronics                | 21        | 0.48%   |
| Primax Electronics                     | 18        | 0.41%   |
| Samsung Electronics                    | 14        | 0.32%   |
| ALi                                    | 13        | 0.3%    |
| Importek                               | 12        | 0.27%   |
| SunplusIT                              | 11        | 0.25%   |
| icSpring                               | 11        | 0.25%   |
| OmniVision Technologies                | 8         | 0.18%   |
| Genesys Logic                          | 8         | 0.18%   |
| Microsoft                              | 7         | 0.16%   |
| GEMBIRD                                | 6         | 0.14%   |
| MacroSilicon                           | 5         | 0.11%   |
| Intel                                  | 5         | 0.11%   |
| Generalplus Technology                 | 5         | 0.11%   |
| Y Media                                | 4         | 0.09%   |
| Sunplus Technology                     | 3         | 0.07%   |
| Pixart Imaging                         | 3         | 0.07%   |
| ARC International                      | 3         | 0.07%   |
| Tobii Technology AB                    | 2         | 0.05%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 288       | 6.54%   |
| Microdia Integrated_Webcam_HD                       | 170       | 3.86%   |
| IMC Networks Integrated Camera                      | 159       | 3.61%   |
| Realtek Integrated_Webcam_HD                        | 130       | 2.95%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 115       | 2.61%   |
| Sunplus Integrated_Webcam_HD                        | 95        | 2.16%   |
| Chicony HD WebCam                                   | 83        | 1.89%   |
| Bison Integrated Camera                             | 80        | 1.82%   |
| Quanta Chromebook HD Camera                         | 71        | 1.61%   |
| Chicony HP HD Camera                                | 63        | 1.43%   |
| Syntek Integrated Camera                            | 55        | 1.25%   |
| Acer BisonCam, NB Pro                               | 52        | 1.18%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 47        | 1.07%   |
| Chicony USB2.0 HD UVC WebCam                        | 47        | 1.07%   |
| Quanta HP TrueVision HD Camera                      | 46        | 1.05%   |
| Quanta HD User Facing                               | 44        | 1%      |
| Lite-On Integrated Camera                           | 44        | 1%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 40        | 0.91%   |
| Acer Integrated Camera                              | 39        | 0.89%   |
| Microdia Integrated Webcam                          | 37        | 0.84%   |
| Bison SunplusIT Integrated Camera                   | 37        | 0.84%   |
| Chicony HD User Facing                              | 36        | 0.82%   |
| Sunplus HD WebCam                                   | 33        | 0.75%   |
| Chicony Integrated Camera (1280x720@30)             | 32        | 0.73%   |
| Quanta HP HD Camera                                 | 31        | 0.7%    |
| Chicony HP TrueVision HD Camera                     | 30        | 0.68%   |
| Lite-On HP HD Camera                                | 29        | 0.66%   |
| Quanta VGA WebCam                                   | 27        | 0.61%   |
| Realtek USB Camera                                  | 26        | 0.59%   |
| Realtek Integrated Webcam                           | 26        | 0.59%   |
| Chicony USB2.0 Camera                               | 26        | 0.59%   |
| Chicony USB 2.0 Camera                              | 25        | 0.57%   |
| Bison HD Webcam                                     | 25        | 0.57%   |
| Chicony HP Truevision HD                            | 24        | 0.55%   |
| Chicony EasyCamera                                  | 24        | 0.55%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 24        | 0.55%   |
| Apple Built-in iSight                               | 23        | 0.52%   |
| Luxvisions Innotech Limited HP HD Camera            | 22        | 0.5%    |
| Chicony USB2.0 VGA UVC WebCam                       | 22        | 0.5%    |
| Chicony Lenovo EasyCamera                           | 22        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 298       | 32.25%  |
| Synaptics                          | 290       | 31.39%  |
| Shenzhen Goodix Technology         | 120       | 12.99%  |
| Upek                               | 56        | 6.06%   |
| AuthenTec                          | 54        | 5.84%   |
| Elan Microelectronics              | 50        | 5.41%   |
| LighTuning Technology              | 28        | 3.03%   |
| STMicroelectronics                 | 19        | 2.06%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 0.43%   |
| Focal-systems.Corp                 | 2         | 0.22%   |
| Samsung Electronics                | 1         | 0.11%   |
| Microsoft                          | 1         | 0.11%   |
| DigitalPersona                     | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 128       | 13.85%  |
| Shenzhen Goodix  FingerPrint Device                                        | 75        | 8.12%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 61        | 6.6%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 59        | 6.39%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 56        | 6.06%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 50        | 5.41%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 43        | 4.65%   |
| Validity Sensors Synaptics WBDI                                            | 25        | 2.71%   |
| Shenzhen Goodix Fingerprint Reader                                         | 24        | 2.6%    |
| Elan ELAN:ARM-M4                                                           | 23        | 2.49%   |
| AuthenTec AES2810                                                          | 23        | 2.49%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 22        | 2.38%   |
| Shenzhen Goodix FingerPrint                                                | 21        | 2.27%   |
| Elan ELAN:Fingerprint                                                      | 20        | 2.16%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 19        | 2.06%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 18        | 1.95%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 17        | 1.84%   |
| STMicroelectronics Fingerprint Reader                                      | 17        | 1.84%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 16        | 1.73%   |
| Synaptics Fingerprint reader [HP G6]                                       | 16        | 1.73%   |
| Validity Sensors VFS491                                                    | 14        | 1.52%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 1.52%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 1.19%   |
| Validity Sensors VFS Fingerprint sensor                                    | 11        | 1.19%   |
| Synaptics UWP WBDI Device                                                  | 11        | 1.19%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 10        | 1.08%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 10        | 1.08%   |
| Validity Sensors Fingerprint scanner                                       | 10        | 1.08%   |
| Synaptics  WBDI                                                            | 9         | 0.97%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 8         | 0.87%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 7         | 0.76%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 0.76%   |
| Elan WBF Fingerprint Sensor                                                | 7         | 0.76%   |
| Upek TCS5B Fingerprint sensor                                              | 6         | 0.65%   |
| Synaptics WBDI                                                             | 6         | 0.65%   |
| Synaptics UWP WBDI                                                         | 5         | 0.54%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.54%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 5         | 0.54%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 0.43%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 0.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 190       | 39.42%  |
| Alcor Micro               | 175       | 36.31%  |
| Upek                      | 34        | 7.05%   |
| Lenovo                    | 32        | 6.64%   |
| O2 Micro                  | 31        | 6.43%   |
| Gemalto (was Gemplus)     | 5         | 1.04%   |
| Yubico.com                | 3         | 0.62%   |
| Clay Logic                | 3         | 0.62%   |
| SCM Microsystems          | 2         | 0.41%   |
| Aladdin Knowledge Systems | 2         | 0.41%   |
| Advanced Card Systems     | 2         | 0.41%   |
| OmniKey                   | 1         | 0.21%   |
| Cherry                    | 1         | 0.21%   |
| C3PO                      | 1         | 0.21%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 172       | 35.68%  |
| Broadcom BCM5880 Secure Applications Processor                               | 53        | 11%     |
| Broadcom 58200                                                               | 51        | 10.58%  |
| Broadcom 5880                                                                | 48        | 9.96%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 36        | 7.47%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 34        | 7.05%   |
| Lenovo Integrated Smart Card Reader                                          | 32        | 6.64%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 26        | 5.39%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 1.04%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 0.62%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.62%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 0.62%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.41%   |
| Clay Logic Nitrokey Start                                                    | 2         | 0.41%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.41%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.41%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.21%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.21%   |
| OmniKey CardMan 4321                                                         | 1         | 0.21%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.21%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.21%   |
| C3PO LTC31v2                                                                 | 1         | 0.21%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.21%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.21%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 3194      | 56.61%  |
| 1     | 1842      | 32.65%  |
| 2     | 480       | 8.51%   |
| 3     | 106       | 1.88%   |
| 4     | 12        | 0.21%   |
| 5     | 7         | 0.12%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 919       | 30.16%  |
| Graphics card            | 789       | 25.89%  |
| Chipcard                 | 444       | 14.57%  |
| Net/wireless             | 274       | 8.99%   |
| Multimedia controller    | 269       | 8.83%   |
| Camera                   | 87        | 2.86%   |
| Bluetooth                | 69        | 2.26%   |
| Card reader              | 44        | 1.44%   |
| Storage                  | 39        | 1.28%   |
| Communication controller | 39        | 1.28%   |
| Sound                    | 24        | 0.79%   |
| Net/ethernet             | 18        | 0.59%   |
| Network                  | 11        | 0.36%   |
| Modem                    | 7         | 0.23%   |
| Flash memory             | 6         | 0.2%    |
| Wireless                 | 2         | 0.07%   |
| Unassigned class         | 2         | 0.07%   |
| Firewire controller      | 2         | 0.07%   |
| Tv card                  | 1         | 0.03%   |
| Storage/ide              | 1         | 0.03%   |

