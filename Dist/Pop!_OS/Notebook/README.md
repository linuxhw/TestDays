Pop!_OS - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

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

Total: 10818

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E14 Gen 7 21U2C... | [51d91615d7](https://linux-hardware.org/?probe=51d91615d7) | Jan 03, 2026 |
| Dell          | Latitude 7490               | [42472aa091](https://linux-hardware.org/?probe=42472aa091) | Jan 03, 2026 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a6b7bccaea](https://linux-hardware.org/?probe=a6b7bccaea) | Jan 03, 2026 |
| Google        | Akemi                       | [fd80c4525c](https://linux-hardware.org/?probe=fd80c4525c) | Jan 03, 2026 |
| Lenovo        | ThinkPad T440 20B7004EUK    | [2403f68590](https://linux-hardware.org/?probe=2403f68590) | Jan 03, 2026 |
| Dell          | Latitude E5470              | [7f142bf72e](https://linux-hardware.org/?probe=7f142bf72e) | Jan 02, 2026 |
| Dell          | Latitude E5470              | [60654750be](https://linux-hardware.org/?probe=60654750be) | Jan 02, 2026 |
| Lenovo        | ThinkPad A485 20MVS03800    | [796ad0a7f2](https://linux-hardware.org/?probe=796ad0a7f2) | Jan 02, 2026 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [752f7202d0](https://linux-hardware.org/?probe=752f7202d0) | Dec 31, 2025 |
| HUAWEI        | BOM-WXX9                    | [e1c9e06b22](https://linux-hardware.org/?probe=e1c9e06b22) | Dec 31, 2025 |
| HUAWEI        | HVY-WXX9                    | [d74dabcc34](https://linux-hardware.org/?probe=d74dabcc34) | Dec 31, 2025 |
| Fujitsu       | LIFEBOOK A514               | [e2a3c805a5](https://linux-hardware.org/?probe=e2a3c805a5) | Dec 30, 2025 |
| Dell          | Pro 14 Plus PB14250         | [436aef9d4e](https://linux-hardware.org/?probe=436aef9d4e) | Dec 30, 2025 |
| Apple         | MacBookPro6,2               | [7a7ff29fba](https://linux-hardware.org/?probe=7a7ff29fba) | Dec 30, 2025 |
| Apple         | MacBookPro6,2               | [0926958b4a](https://linux-hardware.org/?probe=0926958b4a) | Dec 30, 2025 |
| MSI           | GT73VR 7RF                  | [aba4402e58](https://linux-hardware.org/?probe=aba4402e58) | Dec 30, 2025 |
| Dell          | Inspiron 3541               | [c10dcd1d28](https://linux-hardware.org/?probe=c10dcd1d28) | Dec 29, 2025 |
| HP            | Laptop 15s-eq2xxx           | [86fd33cc78](https://linux-hardware.org/?probe=86fd33cc78) | Dec 29, 2025 |
| Toshiba       | TECRA Z50-A                 | [32c23759c8](https://linux-hardware.org/?probe=32c23759c8) | Dec 29, 2025 |
| Dell          | Inspiron 5570               | [0efac634e7](https://linux-hardware.org/?probe=0efac634e7) | Dec 29, 2025 |
| Dell          | Latitude 5400               | [0216bb8035](https://linux-hardware.org/?probe=0216bb8035) | Dec 29, 2025 |
| Razer         | Blade                       | [b1387f76df](https://linux-hardware.org/?probe=b1387f76df) | Dec 29, 2025 |
| Acer          | Aspire A715-43G             | [c7197c1477](https://linux-hardware.org/?probe=c7197c1477) | Dec 29, 2025 |
| Sony          | SVF15A1BCXB                 | [bb4052c955](https://linux-hardware.org/?probe=bb4052c955) | Dec 28, 2025 |
| Acer          | Aspire E1-572G              | [c6ecd95a1b](https://linux-hardware.org/?probe=c6ecd95a1b) | Dec 28, 2025 |
| System76      | Pangolin                    | [69c6f92c89](https://linux-hardware.org/?probe=69c6f92c89) | Dec 28, 2025 |
| Apple         | MacBookPro12,1              | [63ec0146cc](https://linux-hardware.org/?probe=63ec0146cc) | Dec 28, 2025 |
| Apple         | MacBookPro9,2               | [305a0aa40c](https://linux-hardware.org/?probe=305a0aa40c) | Dec 28, 2025 |
| ASUSTek       | ASUS TUF Gaming A14 FA40... | [3cd2a723f5](https://linux-hardware.org/?probe=3cd2a723f5) | Dec 27, 2025 |
| Gigabyte      | Z170N-Gaming 5              | [ee8d31ac61](https://linux-hardware.org/?probe=ee8d31ac61) | Dec 27, 2025 |
| ASUSTek       | GL553VD                     | [0889a8f71a](https://linux-hardware.org/?probe=0889a8f71a) | Dec 27, 2025 |
| Dell          | G7 7588                     | [db4f0c9c08](https://linux-hardware.org/?probe=db4f0c9c08) | Dec 27, 2025 |
| Framework     | Laptop                      | [f68799061a](https://linux-hardware.org/?probe=f68799061a) | Dec 27, 2025 |
| Star Labs     | StarBook                    | [57c1ab9df3](https://linux-hardware.org/?probe=57c1ab9df3) | Dec 26, 2025 |
| HP            | OmniBook X Laptop 17-dd0... | [e34851bd60](https://linux-hardware.org/?probe=e34851bd60) | Dec 26, 2025 |
| Lenovo        | Yoga 3 11 80J8              | [ff5720da27](https://linux-hardware.org/?probe=ff5720da27) | Dec 26, 2025 |
| ASUSTek       | ASUS Zenbook 14 UX3405CA... | [1868dce98f](https://linux-hardware.org/?probe=1868dce98f) | Dec 26, 2025 |
| HP            | OMEN by Laptop 17-an0xx     | [01fbd779d8](https://linux-hardware.org/?probe=01fbd779d8) | Dec 26, 2025 |
| Dell          | Latitude 7290               | [2ab1b03b53](https://linux-hardware.org/?probe=2ab1b03b53) | Dec 26, 2025 |
| ASUSTek       | Strix GL704GW               | [297317bc4f](https://linux-hardware.org/?probe=297317bc4f) | Dec 26, 2025 |
| HP            | EliteBook 840 G6            | [f81f5c4885](https://linux-hardware.org/?probe=f81f5c4885) | Dec 26, 2025 |
| Apple         | MacBook5,2                  | [af68a4c625](https://linux-hardware.org/?probe=af68a4c625) | Dec 25, 2025 |
| Google        | Jinlon                      | [b49ee8ad45](https://linux-hardware.org/?probe=b49ee8ad45) | Dec 25, 2025 |
| Dell          | Vostro 16 5635              | [ce966db0f6](https://linux-hardware.org/?probe=ce966db0f6) | Dec 25, 2025 |
| System76      | Gazelle                     | [f3e752bc4d](https://linux-hardware.org/?probe=f3e752bc4d) | Dec 25, 2025 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [9eb998d759](https://linux-hardware.org/?probe=9eb998d759) | Dec 25, 2025 |
| Apple         | MacBookPro11,5              | [09d99ee98a](https://linux-hardware.org/?probe=09d99ee98a) | Dec 25, 2025 |
| Lenovo        | G500 20236                  | [404ebf223e](https://linux-hardware.org/?probe=404ebf223e) | Dec 25, 2025 |
| HP            | OmniBook X Laptop 17-dd0... | [d727addfb2](https://linux-hardware.org/?probe=d727addfb2) | Dec 24, 2025 |
| Acer          | Nitro ANV15-41              | [7a17abcef8](https://linux-hardware.org/?probe=7a17abcef8) | Dec 24, 2025 |
| HP            | EliteBook 840 G6            | [a03d7d2337](https://linux-hardware.org/?probe=a03d7d2337) | Dec 24, 2025 |
| Acer          | Aspire VN7-593G             | [059d7078c4](https://linux-hardware.org/?probe=059d7078c4) | Dec 23, 2025 |
| Apple         | MacBookAir6,2               | [9eb0435d6b](https://linux-hardware.org/?probe=9eb0435d6b) | Dec 23, 2025 |
| HP            | 15                          | [3e11bcc056](https://linux-hardware.org/?probe=3e11bcc056) | Dec 23, 2025 |
| Apple         | MacBookPro11,1              | [ffa7550e0a](https://linux-hardware.org/?probe=ffa7550e0a) | Dec 23, 2025 |
| ASUSTek       | X550JK                      | [83a132cff6](https://linux-hardware.org/?probe=83a132cff6) | Dec 22, 2025 |
| Acer          | Aspire A315-24P             | [251bc0aff0](https://linux-hardware.org/?probe=251bc0aff0) | Dec 22, 2025 |
| HP            | Laptop 15-fc0xxx            | [091f0afb02](https://linux-hardware.org/?probe=091f0afb02) | Dec 22, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bfe61e1f6a](https://linux-hardware.org/?probe=bfe61e1f6a) | Dec 21, 2025 |
| Apple         | MacBookPro9,2               | [64a3ef7f26](https://linux-hardware.org/?probe=64a3ef7f26) | Dec 21, 2025 |
| HP            | Pavilion dv7                | [2c19c5d034](https://linux-hardware.org/?probe=2c19c5d034) | Dec 21, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [755b8d057f](https://linux-hardware.org/?probe=755b8d057f) | Dec 21, 2025 |
| Monster       | HUMA H4 V6.1                | [a98517af0d](https://linux-hardware.org/?probe=a98517af0d) | Dec 21, 2025 |
| Monster       | HUMA H4 V6.1                | [a1c122c47d](https://linux-hardware.org/?probe=a1c122c47d) | Dec 21, 2025 |
| Lenovo        | G50-80 80L0                 | [d703cc2721](https://linux-hardware.org/?probe=d703cc2721) | Dec 21, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [06d8f2f419](https://linux-hardware.org/?probe=06d8f2f419) | Dec 21, 2025 |
| HP            | Laptop 15-fc0xxx            | [b1193c38c8](https://linux-hardware.org/?probe=b1193c38c8) | Dec 21, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA403UU... | [5a998ab588](https://linux-hardware.org/?probe=5a998ab588) | Dec 21, 2025 |
| ASUSTek       | G750JX                      | [f9d6799459](https://linux-hardware.org/?probe=f9d6799459) | Dec 21, 2025 |
| Dell          | Studio XPS 1340             | [ec3928d9b4](https://linux-hardware.org/?probe=ec3928d9b4) | Dec 21, 2025 |
| PC Special... | X6AR558Y                    | [61d457afc8](https://linux-hardware.org/?probe=61d457afc8) | Dec 20, 2025 |
| HP            | Pavilion dv7                | [18eda031c2](https://linux-hardware.org/?probe=18eda031c2) | Dec 20, 2025 |
| Apple         | MacBookPro9,2               | [005eafea55](https://linux-hardware.org/?probe=005eafea55) | Dec 20, 2025 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [297ab467bd](https://linux-hardware.org/?probe=297ab467bd) | Dec 20, 2025 |
| Lenovo        | ThinkPad T520 42404CG       | [b074073ee3](https://linux-hardware.org/?probe=b074073ee3) | Dec 20, 2025 |
| Lenovo        | ThinkPad T15p Gen 1 20TN... | [52321fecc4](https://linux-hardware.org/?probe=52321fecc4) | Dec 20, 2025 |
| MSI           | GT70 2PC                    | [ffd88a8766](https://linux-hardware.org/?probe=ffd88a8766) | Dec 20, 2025 |
| Dell          | Latitude E6230              | [6aa39f5ba0](https://linux-hardware.org/?probe=6aa39f5ba0) | Dec 20, 2025 |
| PC Special... | Lafite Pro 15 AMD           | [8d495e25e2](https://linux-hardware.org/?probe=8d495e25e2) | Dec 20, 2025 |
| Lenovo        | ThinkPad T440 20B7004EUK    | [41b99981d5](https://linux-hardware.org/?probe=41b99981d5) | Dec 19, 2025 |
| HP            | Pavilion Plus Laptop 14-... | [8cd7ab62b9](https://linux-hardware.org/?probe=8cd7ab62b9) | Dec 19, 2025 |
| ASUSTek       | X751LAB                     | [6cb38a35a5](https://linux-hardware.org/?probe=6cb38a35a5) | Dec 19, 2025 |
| Lenovo        | ThinkPad T440 20B7004EUK    | [732c42fb5e](https://linux-hardware.org/?probe=732c42fb5e) | Dec 19, 2025 |
| Apple         | MacBookPro9,2               | [ad44f617c3](https://linux-hardware.org/?probe=ad44f617c3) | Dec 19, 2025 |
| Lenovo        | Y50-70 20378                | [a917205ad7](https://linux-hardware.org/?probe=a917205ad7) | Dec 18, 2025 |
| Apple         | MacBookPro11,1              | [7e5e3dfc96](https://linux-hardware.org/?probe=7e5e3dfc96) | Dec 18, 2025 |
| Dell          | Inspiron 5402               | [b761587255](https://linux-hardware.org/?probe=b761587255) | Dec 18, 2025 |
| System76      | Darter Pro                  | [1136a615cd](https://linux-hardware.org/?probe=1136a615cd) | Dec 18, 2025 |
| Lenovo        | ThinkPad E16 Gen 3 21SR0... | [b9a1275ba6](https://linux-hardware.org/?probe=b9a1275ba6) | Dec 17, 2025 |
| HP            | Victus by Laptop 16-e0xx... | [9c4738faec](https://linux-hardware.org/?probe=9c4738faec) | Dec 17, 2025 |
| HP            | Victus by Laptop 16-e0xx... | [6fe0087b6f](https://linux-hardware.org/?probe=6fe0087b6f) | Dec 17, 2025 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | [ff470ec7e5](https://linux-hardware.org/?probe=ff470ec7e5) | Dec 17, 2025 |
| Razer         | Blade 15 Advanced Model ... | [a37322d11a](https://linux-hardware.org/?probe=a37322d11a) | Dec 17, 2025 |
| HP            | OMEN by Laptop 15-dh1xxx    | [4afb48efb2](https://linux-hardware.org/?probe=4afb48efb2) | Dec 17, 2025 |
| HP            | OMEN by Laptop 15-dh1xxx    | [7233aeadbb](https://linux-hardware.org/?probe=7233aeadbb) | Dec 17, 2025 |
| Lenovo        | ThinkPad P1 Gen 8 21Q800... | [a758307875](https://linux-hardware.org/?probe=a758307875) | Dec 17, 2025 |
| MSI           | Summit E14Evo A12M          | [2d49308a04](https://linux-hardware.org/?probe=2d49308a04) | Dec 16, 2025 |
| Google        | Laser14                     | [91aa82c6dc](https://linux-hardware.org/?probe=91aa82c6dc) | Dec 16, 2025 |
| Lenovo        | Legion 5 15IAX10 83F0       | [789489ae23](https://linux-hardware.org/?probe=789489ae23) | Dec 16, 2025 |
| HP            | Pavilion Laptop 15-eh1xx... | [f121c369e7](https://linux-hardware.org/?probe=f121c369e7) | Dec 16, 2025 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [bdff06b914](https://linux-hardware.org/?probe=bdff06b914) | Dec 16, 2025 |
| Avell         | 350r                        | [dd8a378bad](https://linux-hardware.org/?probe=dd8a378bad) | Dec 16, 2025 |
| Lenovo        | ThinkPad E470 20H2A083BR    | [f2ac65dba0](https://linux-hardware.org/?probe=f2ac65dba0) | Dec 16, 2025 |
| ASUSTek       | ASUS Zenbook 14 UX3405CA... | [341a6407f6](https://linux-hardware.org/?probe=341a6407f6) | Dec 16, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [8ad2c3fd5c](https://linux-hardware.org/?probe=8ad2c3fd5c) | Dec 15, 2025 |
| Alienware     | M17xR4                      | [d53c636aca](https://linux-hardware.org/?probe=d53c636aca) | Dec 15, 2025 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | [68d637696d](https://linux-hardware.org/?probe=68d637696d) | Dec 15, 2025 |
| HP            | Pavilion 15                 | [3b5b17cf33](https://linux-hardware.org/?probe=3b5b17cf33) | Dec 15, 2025 |
| Apple         | MacBookPro9,2               | [3580e5c6a3](https://linux-hardware.org/?probe=3580e5c6a3) | Dec 14, 2025 |
| Lenovo        | ThinkPad W530 243857U       | [93e57d7342](https://linux-hardware.org/?probe=93e57d7342) | Dec 14, 2025 |
| MSI           | Prestige 16 AI Studio B1... | [eb4bd00e01](https://linux-hardware.org/?probe=eb4bd00e01) | Dec 14, 2025 |
| HP            | Laptop 14-dk0xxx            | [c03e61af95](https://linux-hardware.org/?probe=c03e61af95) | Dec 14, 2025 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [6be8a35324](https://linux-hardware.org/?probe=6be8a35324) | Dec 14, 2025 |
| Acer          | Aspire A315-24P             | [56fb9838ce](https://linux-hardware.org/?probe=56fb9838ce) | Dec 13, 2025 |
| MSI           | Thin 15 B12VE               | [e92adcbcc8](https://linux-hardware.org/?probe=e92adcbcc8) | Dec 13, 2025 |
| Lenovo        | Y40-70 20347                | [15b80e1e91](https://linux-hardware.org/?probe=15b80e1e91) | Dec 13, 2025 |
| Lenovo        | Y40-70 20347                | [50d8db10cb](https://linux-hardware.org/?probe=50d8db10cb) | Dec 13, 2025 |
| Lenovo        | ThinkPad L14 Gen 2 20X20... | [b29aec059d](https://linux-hardware.org/?probe=b29aec059d) | Dec 13, 2025 |
| Samsung       | 750XDA                      | [e9709477e7](https://linux-hardware.org/?probe=e9709477e7) | Dec 13, 2025 |
| Apple         | MacBookPro14,1              | [0642c7e97f](https://linux-hardware.org/?probe=0642c7e97f) | Dec 13, 2025 |
| System76      | Adder WS                    | [6c4c3d426e](https://linux-hardware.org/?probe=6c4c3d426e) | Dec 13, 2025 |
| ASUSTek       | K56CM                       | [e1460005f2](https://linux-hardware.org/?probe=e1460005f2) | Dec 12, 2025 |
| HP            | Pavilion Gaming Laptop 1... | [6374abd589](https://linux-hardware.org/?probe=6374abd589) | Dec 12, 2025 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [d527d95d6f](https://linux-hardware.org/?probe=d527d95d6f) | Dec 12, 2025 |
| MSI           | PRO Z690-A WIFI             | [562e932c3a](https://linux-hardware.org/?probe=562e932c3a) | Dec 11, 2025 |
| Lenovo        | ThinkPad T420 4178BAG       | [e16316c3e2](https://linux-hardware.org/?probe=e16316c3e2) | Dec 10, 2025 |
| Lenovo        | ThinkPad T460s 20FAS0KH0... | [4b6c2b8bd0](https://linux-hardware.org/?probe=4b6c2b8bd0) | Dec 10, 2025 |
| LG Electro... | 17Z990-GPV03                | [d97bee2710](https://linux-hardware.org/?probe=d97bee2710) | Dec 09, 2025 |
| Dell          | Latitude E6510              | [0e61ffb576](https://linux-hardware.org/?probe=0e61ffb576) | Dec 09, 2025 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [1406d5b8ce](https://linux-hardware.org/?probe=1406d5b8ce) | Dec 08, 2025 |
| Apple         | MacBookPro9,1               | [9e1d9798af](https://linux-hardware.org/?probe=9e1d9798af) | Dec 08, 2025 |
| Apple         | MacBookPro9,1               | [edbb6ad45a](https://linux-hardware.org/?probe=edbb6ad45a) | Dec 08, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [5b9be5ec63](https://linux-hardware.org/?probe=5b9be5ec63) | Dec 08, 2025 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [91f31882b9](https://linux-hardware.org/?probe=91f31882b9) | Dec 08, 2025 |
| HP            | ProBook 445 G8 Notebook ... | [5c85ce99c8](https://linux-hardware.org/?probe=5c85ce99c8) | Dec 07, 2025 |
| ASUSTek       | GL553VE                     | [792423abe6](https://linux-hardware.org/?probe=792423abe6) | Dec 07, 2025 |
| Acer          | Nitro ANV15-41              | [0747d333f7](https://linux-hardware.org/?probe=0747d333f7) | Dec 07, 2025 |
| System76      | Kudu                        | [343e4d2304](https://linux-hardware.org/?probe=343e4d2304) | Dec 07, 2025 |
| Acer          | Aspire V7-481P              | [f4f893a793](https://linux-hardware.org/?probe=f4f893a793) | Dec 07, 2025 |
| Acer          | Nitro ANV15-41              | [cf099ccdea](https://linux-hardware.org/?probe=cf099ccdea) | Dec 06, 2025 |
| Dell          | Latitude 5401               | [3168d7525f](https://linux-hardware.org/?probe=3168d7525f) | Dec 06, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [fb31831872](https://linux-hardware.org/?probe=fb31831872) | Dec 06, 2025 |
| Toshiba       | Satellite A300              | [50a0c8532c](https://linux-hardware.org/?probe=50a0c8532c) | Dec 06, 2025 |
| Lenovo        | ThinkPad T440s 20ARS3K60... | [e484da64b7](https://linux-hardware.org/?probe=e484da64b7) | Dec 05, 2025 |
| Dell          | Pro 16 Plus PB16255         | [2a31ed9ec3](https://linux-hardware.org/?probe=2a31ed9ec3) | Dec 04, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [a77f953076](https://linux-hardware.org/?probe=a77f953076) | Dec 04, 2025 |
| Acer          | Nitro AN515-45              | [7d7962356d](https://linux-hardware.org/?probe=7d7962356d) | Dec 04, 2025 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [d858bcbd94](https://linux-hardware.org/?probe=d858bcbd94) | Dec 04, 2025 |
| Samsung       | 550XDA                      | [dc3a0648fa](https://linux-hardware.org/?probe=dc3a0648fa) | Dec 04, 2025 |
| System76      | Darter Pro                  | [21b9b327c2](https://linux-hardware.org/?probe=21b9b327c2) | Dec 04, 2025 |
| HP            | 15                          | [0322173c14](https://linux-hardware.org/?probe=0322173c14) | Dec 02, 2025 |
| HP            | 15                          | [da5232ce02](https://linux-hardware.org/?probe=da5232ce02) | Dec 02, 2025 |
| ASUSTek       | X555LJ                      | [3c12e5e01b](https://linux-hardware.org/?probe=3c12e5e01b) | Nov 30, 2025 |
| HP            | Laptop 14-ck2xxx            | [62525d79fc](https://linux-hardware.org/?probe=62525d79fc) | Nov 29, 2025 |
| Google        | Volet                       | [dba215a8ea](https://linux-hardware.org/?probe=dba215a8ea) | Nov 29, 2025 |
| Panasonic     | CF-31WB91TFM                | [577b0783d3](https://linux-hardware.org/?probe=577b0783d3) | Nov 28, 2025 |
| ASUSTek       | N501VW                      | [218eecb3bb](https://linux-hardware.org/?probe=218eecb3bb) | Nov 28, 2025 |
| Lenovo        | ThinkPad T480 20L6S42300    | [90a2ec7f39](https://linux-hardware.org/?probe=90a2ec7f39) | Nov 28, 2025 |
| System76      | Bonobo WS                   | [1ac83f26c0](https://linux-hardware.org/?probe=1ac83f26c0) | Nov 27, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [f3dfdebe8e](https://linux-hardware.org/?probe=f3dfdebe8e) | Nov 26, 2025 |
| Lenovo        | Legion Pro 5 16ADR10 83L... | [8f4ede36af](https://linux-hardware.org/?probe=8f4ede36af) | Nov 26, 2025 |
| MSI           | Thin 15 B13UC               | [6776dfcf29](https://linux-hardware.org/?probe=6776dfcf29) | Nov 26, 2025 |
| Lenovo        | Yoga Pro 7 14AHP9 83E3      | [269a52cf1d](https://linux-hardware.org/?probe=269a52cf1d) | Nov 25, 2025 |
| MSI           | GF63 Thin 10UD              | [76ae648a67](https://linux-hardware.org/?probe=76ae648a67) | Nov 25, 2025 |
| TongFang      | GX5MRXL                     | [ea88de111d](https://linux-hardware.org/?probe=ea88de111d) | Nov 24, 2025 |
| ASUSTek       | GL752VW                     | [78933458ca](https://linux-hardware.org/?probe=78933458ca) | Nov 23, 2025 |
| HP            | Laptop 15-bs0xx             | [b441b41b34](https://linux-hardware.org/?probe=b441b41b34) | Nov 22, 2025 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [d7b549283e](https://linux-hardware.org/?probe=d7b549283e) | Nov 22, 2025 |
| ASUSTek       | GL552VW                     | [26f205d4ad](https://linux-hardware.org/?probe=26f205d4ad) | Nov 22, 2025 |
| SIEMENS       | SIMATIC Field PG M2         | [eca5a420e8](https://linux-hardware.org/?probe=eca5a420e8) | Nov 21, 2025 |
| Apple         | MacBookAir7,2               | [17b46cb92c](https://linux-hardware.org/?probe=17b46cb92c) | Nov 21, 2025 |
| Alienware     | M17xR4                      | [17fad449e7](https://linux-hardware.org/?probe=17fad449e7) | Nov 21, 2025 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [7785d53587](https://linux-hardware.org/?probe=7785d53587) | Nov 20, 2025 |
| Lenovo        | ThinkPad X260 20F5S5E200    | [1bee0e8895](https://linux-hardware.org/?probe=1bee0e8895) | Nov 19, 2025 |
| Lenovo        | ThinkPad L13 Gen 2 20VJ0... | [08a0993e67](https://linux-hardware.org/?probe=08a0993e67) | Nov 19, 2025 |
| Novatech      | P65_67RSRP                  | [65b61d4558](https://linux-hardware.org/?probe=65b61d4558) | Nov 19, 2025 |
| HP            | Laptop 15-fc0xxx            | [32ef98c225](https://linux-hardware.org/?probe=32ef98c225) | Nov 18, 2025 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | [7229df3f9d](https://linux-hardware.org/?probe=7229df3f9d) | Nov 17, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [7ad3e3af10](https://linux-hardware.org/?probe=7ad3e3af10) | Nov 17, 2025 |
| Lenovo        | ThinkPad T430 2342CTO       | [1b53d1b84c](https://linux-hardware.org/?probe=1b53d1b84c) | Nov 17, 2025 |
| MSI           | GP62 6QE                    | [7569598435](https://linux-hardware.org/?probe=7569598435) | Nov 17, 2025 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [450c917ed3](https://linux-hardware.org/?probe=450c917ed3) | Nov 15, 2025 |
| GPU Compan... | GWTN141-10                  | [162bf83945](https://linux-hardware.org/?probe=162bf83945) | Nov 15, 2025 |
| Dell          | Inspiron 5559               | [5bde4bcb56](https://linux-hardware.org/?probe=5bde4bcb56) | Nov 14, 2025 |
| PC Special... | Standard                    | [dcffada0f7](https://linux-hardware.org/?probe=dcffada0f7) | Nov 14, 2025 |
| Dell          | Latitude E5470              | [ea504a74cc](https://linux-hardware.org/?probe=ea504a74cc) | Nov 14, 2025 |
| Acer          | Nitro ANV15-51              | [abf3c85360](https://linux-hardware.org/?probe=abf3c85360) | Nov 13, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [3ee9e47377](https://linux-hardware.org/?probe=3ee9e47377) | Nov 12, 2025 |
| HP            | Spectre Pro x360 G2         | [5d4c553ea0](https://linux-hardware.org/?probe=5d4c553ea0) | Nov 12, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [b0edef25ef](https://linux-hardware.org/?probe=b0edef25ef) | Nov 12, 2025 |
| Dell          | Vostro 15 3510              | [c130697ced](https://linux-hardware.org/?probe=c130697ced) | Nov 12, 2025 |
| ASUSTek       | ASUS TUF Gaming A16 FA60... | [eb20e28600](https://linux-hardware.org/?probe=eb20e28600) | Nov 12, 2025 |
| HP            | Pavilion dv6                | [b40aa4d651](https://linux-hardware.org/?probe=b40aa4d651) | Nov 12, 2025 |
| HP            | Pavilion dv6                | [8149bfcaf0](https://linux-hardware.org/?probe=8149bfcaf0) | Nov 12, 2025 |
| Apple         | MacBookPro8,1               | [ff3931a1d8](https://linux-hardware.org/?probe=ff3931a1d8) | Nov 12, 2025 |
| Dell          | G5 5587                     | [fa3534d695](https://linux-hardware.org/?probe=fa3534d695) | Nov 11, 2025 |
| Apple         | MacBookPro10,1              | [58f9ed8a15](https://linux-hardware.org/?probe=58f9ed8a15) | Nov 11, 2025 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [26f4e7fa03](https://linux-hardware.org/?probe=26f4e7fa03) | Nov 10, 2025 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [fbc7e7c93c](https://linux-hardware.org/?probe=fbc7e7c93c) | Nov 10, 2025 |
| Dell          | Inspiron 5559               | [d433c6be01](https://linux-hardware.org/?probe=d433c6be01) | Nov 10, 2025 |
| Acer          | Nitro AN515-58              | [143b87d1fa](https://linux-hardware.org/?probe=143b87d1fa) | Nov 09, 2025 |
| HP            | Victus by Gaming Laptop ... | [9482407841](https://linux-hardware.org/?probe=9482407841) | Nov 09, 2025 |
| Acer          | Nitro AN515-52              | [3aedcd3bbf](https://linux-hardware.org/?probe=3aedcd3bbf) | Nov 08, 2025 |
| Dell          | Inspiron 5420               | [df8c24bc92](https://linux-hardware.org/?probe=df8c24bc92) | Nov 08, 2025 |
| Acer          | Aspire A517-51              | [ee9d4faa34](https://linux-hardware.org/?probe=ee9d4faa34) | Nov 07, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [5c3a4a6731](https://linux-hardware.org/?probe=5c3a4a6731) | Nov 07, 2025 |
| Lenovo        | Yoga 2 13 20344             | [ff2c624155](https://linux-hardware.org/?probe=ff2c624155) | Nov 06, 2025 |
| Acer          | Nitro AN517-54              | [adc57d859c](https://linux-hardware.org/?probe=adc57d859c) | Nov 05, 2025 |
| Lenovo        | ThinkPad X395 20NMS0YF00    | [abd881e5b4](https://linux-hardware.org/?probe=abd881e5b4) | Nov 05, 2025 |
| Acer          | TravelMate P259-M           | [fd2fb3a425](https://linux-hardware.org/?probe=fd2fb3a425) | Nov 05, 2025 |
| Acer          | TravelMate P259-M           | [e3c5b73ea5](https://linux-hardware.org/?probe=e3c5b73ea5) | Nov 05, 2025 |
| HUAWEI        | WRT-WX9                     | [ce057ca73d](https://linux-hardware.org/?probe=ce057ca73d) | Nov 05, 2025 |
| Dell          | Inspiron 1545               | [1591a14b52](https://linux-hardware.org/?probe=1591a14b52) | Nov 03, 2025 |
| Apple         | MacBookPro11,3              | [7cd39452f2](https://linux-hardware.org/?probe=7cd39452f2) | Nov 03, 2025 |
| Acer          | Aspire A515-41G             | [f00f5c43a6](https://linux-hardware.org/?probe=f00f5c43a6) | Nov 03, 2025 |
| Acer          | Nitro AN515-43              | [f7d3b086b8](https://linux-hardware.org/?probe=f7d3b086b8) | Nov 02, 2025 |
| HP            | 255R 15.6 inch G10 Noteb... | [98e59fc506](https://linux-hardware.org/?probe=98e59fc506) | Nov 02, 2025 |
| Dell          | Inspiron 7559               | [1651066ba0](https://linux-hardware.org/?probe=1651066ba0) | Nov 01, 2025 |
| Apple         | MacBookPro11,3              | [37770f9c3b](https://linux-hardware.org/?probe=37770f9c3b) | Oct 31, 2025 |
| Dell          | Inspiron 7577               | [a60a901cde](https://linux-hardware.org/?probe=a60a901cde) | Oct 31, 2025 |
| HP            | ProBook 455 15.6 inch G1... | [3694ccaf63](https://linux-hardware.org/?probe=3694ccaf63) | Oct 31, 2025 |
| ASUSTek       | G750JM                      | [d85db49611](https://linux-hardware.org/?probe=d85db49611) | Oct 31, 2025 |
| Dell          | Latitude E5470              | [8d9999b2c7](https://linux-hardware.org/?probe=8d9999b2c7) | Oct 30, 2025 |
| Dell          | Inspiron 3558               | [1d2cc9f24a](https://linux-hardware.org/?probe=1d2cc9f24a) | Oct 30, 2025 |
| ASUSTek       | G750JM                      | [af826bdb3b](https://linux-hardware.org/?probe=af826bdb3b) | Oct 30, 2025 |
| ASUSTek       | X750JB                      | [f9fcacc64a](https://linux-hardware.org/?probe=f9fcacc64a) | Oct 29, 2025 |
| MSI           | PRO B650M-P                 | [41c89f7d32](https://linux-hardware.org/?probe=41c89f7d32) | Oct 29, 2025 |
| HP            | Victus by Gaming Laptop ... | [c056d7e704](https://linux-hardware.org/?probe=c056d7e704) | Oct 28, 2025 |
| Unknown       | Unknown                     | [6324a95442](https://linux-hardware.org/?probe=6324a95442) | Oct 28, 2025 |
| ASUSTek       | Zenbook UX3404VA_Q420VA     | [7cd36b25bd](https://linux-hardware.org/?probe=7cd36b25bd) | Oct 28, 2025 |
| MSI           | Raider GE78HX 13VG          | [577de92c78](https://linux-hardware.org/?probe=577de92c78) | Oct 28, 2025 |
| Lenovo        | ThinkPad X250 20CMA03VHH    | [da27460399](https://linux-hardware.org/?probe=da27460399) | Oct 27, 2025 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [70b0413204](https://linux-hardware.org/?probe=70b0413204) | Oct 27, 2025 |
| Lenovo        | ThinkPad X250 20CMA03VHH    | [b2b1b4f09c](https://linux-hardware.org/?probe=b2b1b4f09c) | Oct 26, 2025 |
| Dell          | Inspiron 3551               | [8f9ba33ef1](https://linux-hardware.org/?probe=8f9ba33ef1) | Oct 26, 2025 |
| Apple         | MacBookPro11,1              | [6779d87d3c](https://linux-hardware.org/?probe=6779d87d3c) | Oct 26, 2025 |
| Apple         | MacBookPro11,1              | [88f73b217d](https://linux-hardware.org/?probe=88f73b217d) | Oct 25, 2025 |
| HP            | Victus by Laptop 16-e0xx... | [33f82d394b](https://linux-hardware.org/?probe=33f82d394b) | Oct 25, 2025 |
| ASUSTek       | ROG Strix G16 G614PR_G61... | [37ca4c334d](https://linux-hardware.org/?probe=37ca4c334d) | Oct 24, 2025 |
| Gigabyte      | Q2432M                      | [d7ed236336](https://linux-hardware.org/?probe=d7ed236336) | Oct 24, 2025 |
| Gigabyte      | Z170N-Gaming 5              | [b7211ed996](https://linux-hardware.org/?probe=b7211ed996) | Oct 23, 2025 |
| Timi          | Mi Laptop Pro 15            | [bd95569a02](https://linux-hardware.org/?probe=bd95569a02) | Oct 23, 2025 |
| System76      | Oryx Pro                    | [8cc15aaeaf](https://linux-hardware.org/?probe=8cc15aaeaf) | Oct 23, 2025 |
| Acer          | Aspire A515-45              | [3cb422437c](https://linux-hardware.org/?probe=3cb422437c) | Oct 22, 2025 |
| HP            | EliteBook 850 G5            | [187ad354a0](https://linux-hardware.org/?probe=187ad354a0) | Oct 22, 2025 |
| Apple         | MacBookPro14,3              | [531e9f22bf](https://linux-hardware.org/?probe=531e9f22bf) | Oct 22, 2025 |
| Dell          | XPS 9320                    | [2e806f33a7](https://linux-hardware.org/?probe=2e806f33a7) | Oct 22, 2025 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [1162e01f43](https://linux-hardware.org/?probe=1162e01f43) | Oct 21, 2025 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b1a5cd062d](https://linux-hardware.org/?probe=b1a5cd062d) | Oct 19, 2025 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a67169b1f7](https://linux-hardware.org/?probe=a67169b1f7) | Oct 19, 2025 |
| Lenovo        | ThinkPad X280 20KESBL212    | [7e86893e24](https://linux-hardware.org/?probe=7e86893e24) | Oct 19, 2025 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d4ceda7b1f](https://linux-hardware.org/?probe=d4ceda7b1f) | Oct 19, 2025 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [9986ff06ec](https://linux-hardware.org/?probe=9986ff06ec) | Oct 19, 2025 |
| Apple         | MacBookPro16,2              | [15dee65c7f](https://linux-hardware.org/?probe=15dee65c7f) | Oct 19, 2025 |
| Lenovo        | Legion 5 Pro 16IAH7 82S0    | [1167e372aa](https://linux-hardware.org/?probe=1167e372aa) | Oct 18, 2025 |
| Lenovo        | V15 G2 IJL 82QY             | [f99bf36d26](https://linux-hardware.org/?probe=f99bf36d26) | Oct 18, 2025 |
| ASUSTek       | X542UAR                     | [0f43076953](https://linux-hardware.org/?probe=0f43076953) | Oct 18, 2025 |
| ASUSTek       | X542UAR                     | [106a113cb9](https://linux-hardware.org/?probe=106a113cb9) | Oct 18, 2025 |
| Acer          | Aspire A315-24P             | [dff9bd1563](https://linux-hardware.org/?probe=dff9bd1563) | Oct 18, 2025 |
| ASUSTek       | GL552VW                     | [bdbf41c651](https://linux-hardware.org/?probe=bdbf41c651) | Oct 17, 2025 |
| Acer          | Aspire A315-24P             | [621c2dccf9](https://linux-hardware.org/?probe=621c2dccf9) | Oct 17, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0de54a78a5](https://linux-hardware.org/?probe=0de54a78a5) | Oct 16, 2025 |
| Lenovo        | Legion Pro 5 16ADR10 83L... | [d8fd0c5623](https://linux-hardware.org/?probe=d8fd0c5623) | Oct 16, 2025 |
| ASUSTek       | GL552VX                     | [f57fa6bf75](https://linux-hardware.org/?probe=f57fa6bf75) | Oct 15, 2025 |
| Apple         | MacBookAir7,2               | [5b1c3dd71b](https://linux-hardware.org/?probe=5b1c3dd71b) | Oct 15, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [07a638d182](https://linux-hardware.org/?probe=07a638d182) | Oct 15, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [190ec7b2a9](https://linux-hardware.org/?probe=190ec7b2a9) | Oct 15, 2025 |
| Lenovo        | 14w Gen 2 82N9              | [7405452bf1](https://linux-hardware.org/?probe=7405452bf1) | Oct 14, 2025 |
| HP            | Pavilion Notebook           | [d885387d06](https://linux-hardware.org/?probe=d885387d06) | Oct 14, 2025 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [9622cb9b0a](https://linux-hardware.org/?probe=9622cb9b0a) | Oct 14, 2025 |
| Toshiba       | Satellite Pro L450          | [b3f3e56595](https://linux-hardware.org/?probe=b3f3e56595) | Oct 13, 2025 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | [8b1cd3d9aa](https://linux-hardware.org/?probe=8b1cd3d9aa) | Oct 13, 2025 |
| HP            | Pavilion dv6                | [69bfabc62a](https://linux-hardware.org/?probe=69bfabc62a) | Oct 13, 2025 |
| Lenovo        | V130-14IGM 81HM             | [122738a4fb](https://linux-hardware.org/?probe=122738a4fb) | Oct 13, 2025 |
| ASUSTek       | Q302LA                      | [b26c7fe470](https://linux-hardware.org/?probe=b26c7fe470) | Oct 13, 2025 |
| ASUSTek       | N550JV                      | [f3cd853d66](https://linux-hardware.org/?probe=f3cd853d66) | Oct 12, 2025 |
| ASUSTek       | G750JX                      | [baa25ae52f](https://linux-hardware.org/?probe=baa25ae52f) | Oct 12, 2025 |
| AXIOO         | Mybook Hype 5 AMD           | [7638cca9f5](https://linux-hardware.org/?probe=7638cca9f5) | Oct 12, 2025 |
| HP            | Pavilion dv6                | [d1231e1a26](https://linux-hardware.org/?probe=d1231e1a26) | Oct 12, 2025 |
| Google        | Kano                        | [47b78d5097](https://linux-hardware.org/?probe=47b78d5097) | Oct 12, 2025 |
| AXIOO         | Mybook Hype 5 AMD           | [bcabd89eee](https://linux-hardware.org/?probe=bcabd89eee) | Oct 12, 2025 |
| HP            | Victus by Laptop 16-e0xx... | [76b40af27d](https://linux-hardware.org/?probe=76b40af27d) | Oct 11, 2025 |
| ASUSTek       | G750JX                      | [f94027975d](https://linux-hardware.org/?probe=f94027975d) | Oct 11, 2025 |
| Alienware     | 15 R3                       | [f98229db74](https://linux-hardware.org/?probe=f98229db74) | Oct 10, 2025 |
| System76      | Pangolin                    | [0853a09e2c](https://linux-hardware.org/?probe=0853a09e2c) | Oct 10, 2025 |
| Gigabyte      | AERO 15XV8                  | [4422e3170a](https://linux-hardware.org/?probe=4422e3170a) | Oct 09, 2025 |
| MSI           | Raider 18 HX AI A2XWIG      | [ec60a4ddf0](https://linux-hardware.org/?probe=ec60a4ddf0) | Oct 09, 2025 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [9d12f5c210](https://linux-hardware.org/?probe=9d12f5c210) | Oct 09, 2025 |
| Lenovo        | IdeaPad Slim 5 16AKP10 8... | [48256c6580](https://linux-hardware.org/?probe=48256c6580) | Oct 08, 2025 |
| Dell          | Inspiron 5584               | [b92b86e6c1](https://linux-hardware.org/?probe=b92b86e6c1) | Oct 08, 2025 |
| Dell          | Inspiron 5584               | [3854293ef5](https://linux-hardware.org/?probe=3854293ef5) | Oct 08, 2025 |
| System76      | Pangolin                    | [db6eb68e15](https://linux-hardware.org/?probe=db6eb68e15) | Oct 07, 2025 |
| HP            | ZBook Firefly 15 G7 Mobi... | [30bb9ebd08](https://linux-hardware.org/?probe=30bb9ebd08) | Oct 06, 2025 |
| HP            | EliteBook 850 G2            | [ab26bded85](https://linux-hardware.org/?probe=ab26bded85) | Oct 06, 2025 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [9899d172db](https://linux-hardware.org/?probe=9899d172db) | Oct 05, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [8fd82ecdaa](https://linux-hardware.org/?probe=8fd82ecdaa) | Oct 05, 2025 |
| HP            | EliteBook 850 G2            | [b253442711](https://linux-hardware.org/?probe=b253442711) | Oct 05, 2025 |
| Google        | Osiris                      | [bddf80eec3](https://linux-hardware.org/?probe=bddf80eec3) | Oct 05, 2025 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [62d7416ff3](https://linux-hardware.org/?probe=62d7416ff3) | Oct 04, 2025 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [0f5eb683d5](https://linux-hardware.org/?probe=0f5eb683d5) | Oct 04, 2025 |
| Lenovo        | V130-14IGM 81HM             | [bbbe41fd8d](https://linux-hardware.org/?probe=bbbe41fd8d) | Oct 04, 2025 |
| Alienware     | 15 R3                       | [67b5a1ab45](https://linux-hardware.org/?probe=67b5a1ab45) | Oct 04, 2025 |
| Apple         | MacBookPro14,1              | [8e3129a05c](https://linux-hardware.org/?probe=8e3129a05c) | Oct 04, 2025 |
| MSI           | Thin 15 B12UCX              | [1813ba8f32](https://linux-hardware.org/?probe=1813ba8f32) | Oct 03, 2025 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [fdb617a02c](https://linux-hardware.org/?probe=fdb617a02c) | Oct 03, 2025 |
| Acer          | Aspire A315-59              | [237fef86c6](https://linux-hardware.org/?probe=237fef86c6) | Oct 02, 2025 |
| Acer          | Aspire A315-59              | [e9967e6aca](https://linux-hardware.org/?probe=e9967e6aca) | Oct 02, 2025 |
| ASUSTek       | G751JY                      | [339328a6f3](https://linux-hardware.org/?probe=339328a6f3) | Oct 02, 2025 |
| Alienware     | 17 R4                       | [c280da3eef](https://linux-hardware.org/?probe=c280da3eef) | Oct 01, 2025 |
| HP            | Pavilion Aero Laptop 13-... | [62ce33cf19](https://linux-hardware.org/?probe=62ce33cf19) | Sep 30, 2025 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [35f3d1fa8e](https://linux-hardware.org/?probe=35f3d1fa8e) | Sep 30, 2025 |
| HP            | Pavilion Power Laptop 15... | [d883af4704](https://linux-hardware.org/?probe=d883af4704) | Sep 30, 2025 |
| Lenovo        | ThinkPad T470s 20HFCT01W... | [77e99df618](https://linux-hardware.org/?probe=77e99df618) | Sep 30, 2025 |
| Alienware     | 17 R3                       | [66840f8eda](https://linux-hardware.org/?probe=66840f8eda) | Sep 29, 2025 |
| HP            | 15                          | [c770879416](https://linux-hardware.org/?probe=c770879416) | Sep 29, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [6869b0a724](https://linux-hardware.org/?probe=6869b0a724) | Sep 29, 2025 |
| Dell          | XPS 15 9510                 | [4ea379bba1](https://linux-hardware.org/?probe=4ea379bba1) | Sep 29, 2025 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [e53f6b5af7](https://linux-hardware.org/?probe=e53f6b5af7) | Sep 29, 2025 |
| Acer          | Aspire A315-57G             | [ff753de962](https://linux-hardware.org/?probe=ff753de962) | Sep 28, 2025 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [5b23458051](https://linux-hardware.org/?probe=5b23458051) | Sep 28, 2025 |
| System76      | Darter Pro                  | [93e47e0ea8](https://linux-hardware.org/?probe=93e47e0ea8) | Sep 28, 2025 |
| ASUSTek       | K52Jr                       | [ebd100c700](https://linux-hardware.org/?probe=ebd100c700) | Sep 28, 2025 |
| ASUSTek       | K52Jr                       | [03eb120b31](https://linux-hardware.org/?probe=03eb120b31) | Sep 28, 2025 |
| Toshiba       | Satellite C75D-B            | [5d98b6e7fc](https://linux-hardware.org/?probe=5d98b6e7fc) | Sep 28, 2025 |
| System76      | Galago Pro                  | [25170bbf0b](https://linux-hardware.org/?probe=25170bbf0b) | Sep 28, 2025 |
| HUAWEI        | HVY-WXX9                    | [2b2abd6b25](https://linux-hardware.org/?probe=2b2abd6b25) | Sep 27, 2025 |
| System76      | Adder WS                    | [9e5cb93bfd](https://linux-hardware.org/?probe=9e5cb93bfd) | Sep 27, 2025 |
| System76      | Adder WS                    | [95c8214086](https://linux-hardware.org/?probe=95c8214086) | Sep 27, 2025 |
| HP            | Pavilion Laptop 15-eh1xx... | [811cff1bd8](https://linux-hardware.org/?probe=811cff1bd8) | Sep 27, 2025 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [54003117c4](https://linux-hardware.org/?probe=54003117c4) | Sep 27, 2025 |
| HP            | Pavilion Laptop 15-cs1xx... | [d255281ce9](https://linux-hardware.org/?probe=d255281ce9) | Sep 26, 2025 |
| Unknown       | AX16                        | [f726e79267](https://linux-hardware.org/?probe=f726e79267) | Sep 25, 2025 |
| HP            | OMEN by Laptop 15-dc0xxx    | [3d69eba5d8](https://linux-hardware.org/?probe=3d69eba5d8) | Sep 25, 2025 |
| Lenovo        | ThinkPad X260 20F6006XUK    | [61f9c39c6b](https://linux-hardware.org/?probe=61f9c39c6b) | Sep 25, 2025 |
| HP            | EliteBook 840 G3            | [ca1ccdb44c](https://linux-hardware.org/?probe=ca1ccdb44c) | Sep 25, 2025 |
| Dell          | Latitude 5290 2-in-1        | [4d0b21ca58](https://linux-hardware.org/?probe=4d0b21ca58) | Sep 24, 2025 |
| Dell          | Latitude 5290 2-in-1        | [8f4940716a](https://linux-hardware.org/?probe=8f4940716a) | Sep 24, 2025 |
| Chuwi         | CoreBook X                  | [06cf58ce96](https://linux-hardware.org/?probe=06cf58ce96) | Sep 23, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [2d4415cdad](https://linux-hardware.org/?probe=2d4415cdad) | Sep 23, 2025 |
| HP            | EliteBook 840 G3 Y2Q29UP    | [3cd7fdcebd](https://linux-hardware.org/?probe=3cd7fdcebd) | Sep 23, 2025 |
| HP            | EliteBook 840 G3 Y2Q29UP    | [1326cd8d09](https://linux-hardware.org/?probe=1326cd8d09) | Sep 23, 2025 |
| HP            | 894A 10                     | [8088421b09](https://linux-hardware.org/?probe=8088421b09) | Sep 22, 2025 |
| ASUSTek       | ASUS V16 V3607VH_V3607VH    | [9d18be4221](https://linux-hardware.org/?probe=9d18be4221) | Sep 21, 2025 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [71740d836c](https://linux-hardware.org/?probe=71740d836c) | Sep 20, 2025 |
| ASUSTek       | ROG Strix G531GV_G531GV     | [eb6e349b90](https://linux-hardware.org/?probe=eb6e349b90) | Sep 20, 2025 |
| HP            | Pavilion Aero Laptop 13-... | [a33c158e83](https://linux-hardware.org/?probe=a33c158e83) | Sep 20, 2025 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [61e4fbea47](https://linux-hardware.org/?probe=61e4fbea47) | Sep 20, 2025 |
| HP            | Victus by Gaming Laptop ... | [c1ca57c81b](https://linux-hardware.org/?probe=c1ca57c81b) | Sep 20, 2025 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [b2518bb0e5](https://linux-hardware.org/?probe=b2518bb0e5) | Sep 20, 2025 |
| HP            | Victus by Gaming Laptop ... | [43093c7216](https://linux-hardware.org/?probe=43093c7216) | Sep 19, 2025 |
| Dell          | Latitude 5300               | [fd3f70070b](https://linux-hardware.org/?probe=fd3f70070b) | Sep 19, 2025 |
| HP            | Pavilion Gaming Laptop 1... | [1e4b5219a8](https://linux-hardware.org/?probe=1e4b5219a8) | Sep 19, 2025 |
| Lenovo        | ThinkPad E490 20N80006AD    | [58873d4a7c](https://linux-hardware.org/?probe=58873d4a7c) | Sep 18, 2025 |
| Dell          | Latitude 5300               | [9c6489b4c4](https://linux-hardware.org/?probe=9c6489b4c4) | Sep 18, 2025 |
| Lenovo        | ThinkPad X9-14 Gen 1 21Q... | [39876fc827](https://linux-hardware.org/?probe=39876fc827) | Sep 18, 2025 |
| Lenovo        | IdeaPad 1 15IAU7 82VY       | [bd7eb0c153](https://linux-hardware.org/?probe=bd7eb0c153) | Sep 17, 2025 |
| Dell          | Pro 14 Plus PB14250         | [0c9a5a7368](https://linux-hardware.org/?probe=0c9a5a7368) | Sep 17, 2025 |
| ASUSTek       | ROG Strix G531GV_G531GV     | [d09ad6a8dd](https://linux-hardware.org/?probe=d09ad6a8dd) | Sep 16, 2025 |
| HP            | OMEN by Laptop 15-ce0xx     | [a08ee6c630](https://linux-hardware.org/?probe=a08ee6c630) | Sep 16, 2025 |
| Dell          | Inspiron N5110              | [cc981ff69a](https://linux-hardware.org/?probe=cc981ff69a) | Sep 16, 2025 |
| HP            | Victus by Gaming Laptop ... | [f1d8834c2c](https://linux-hardware.org/?probe=f1d8834c2c) | Sep 16, 2025 |
| HP            | 15                          | [ff431a5619](https://linux-hardware.org/?probe=ff431a5619) | Sep 15, 2025 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | [493bc4fb5c](https://linux-hardware.org/?probe=493bc4fb5c) | Sep 14, 2025 |
| Dell          | Latitude E5540              | [546e2a45d8](https://linux-hardware.org/?probe=546e2a45d8) | Sep 14, 2025 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [aad39cd43b](https://linux-hardware.org/?probe=aad39cd43b) | Sep 14, 2025 |
| Apple         | MacBookAir6,2               | [6102c1fe2c](https://linux-hardware.org/?probe=6102c1fe2c) | Sep 13, 2025 |
| System76      | Darter Pro                  | [ea73200ad1](https://linux-hardware.org/?probe=ea73200ad1) | Sep 13, 2025 |
| Dell          | Precision 7670              | [97364bbe98](https://linux-hardware.org/?probe=97364bbe98) | Sep 12, 2025 |
| Dell          | Inspiron N5110              | [c22cb6375c](https://linux-hardware.org/?probe=c22cb6375c) | Sep 12, 2025 |
| Dell          | Inspiron N5110              | [423987696b](https://linux-hardware.org/?probe=423987696b) | Sep 12, 2025 |
| Dell          | Pro 14 Plus PB14250         | [601e9f576e](https://linux-hardware.org/?probe=601e9f576e) | Sep 11, 2025 |
| ASUSTek       | X541UVK                     | [bda837e806](https://linux-hardware.org/?probe=bda837e806) | Sep 11, 2025 |
| Dell          | Pro Max 16 Premium MA162... | [823574cc07](https://linux-hardware.org/?probe=823574cc07) | Sep 11, 2025 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [8fe1178583](https://linux-hardware.org/?probe=8fe1178583) | Sep 11, 2025 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [d080073069](https://linux-hardware.org/?probe=d080073069) | Sep 11, 2025 |
| Dell          | Precision 3571              | [775d877896](https://linux-hardware.org/?probe=775d877896) | Sep 11, 2025 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ab02cb504d](https://linux-hardware.org/?probe=ab02cb504d) | Sep 10, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | [b262c6617f](https://linux-hardware.org/?probe=b262c6617f) | Sep 10, 2025 |
| MSI           | GF75 Thin 10SCSXR           | [3673e61f21](https://linux-hardware.org/?probe=3673e61f21) | Sep 10, 2025 |
| Samsung       | 340XAA/350XAA/550XAA        | [6228fcbc78](https://linux-hardware.org/?probe=6228fcbc78) | Sep 10, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8f5ba85a93](https://linux-hardware.org/?probe=8f5ba85a93) | Sep 09, 2025 |
| Packard Be... | ENBFXS                      | [79eb425f5d](https://linux-hardware.org/?probe=79eb425f5d) | Sep 09, 2025 |
| Dell          | G5 5587                     | [58f00d3e45](https://linux-hardware.org/?probe=58f00d3e45) | Sep 08, 2025 |
| Apple         | MacBookAir7,2               | [ee893f6f70](https://linux-hardware.org/?probe=ee893f6f70) | Sep 07, 2025 |
| Acer          | Predator PT314-51s          | [662ce9b54b](https://linux-hardware.org/?probe=662ce9b54b) | Sep 07, 2025 |
| Lenovo        | ThinkPad L13 Gen 1 20R40... | [c9c3c8f6b8](https://linux-hardware.org/?probe=c9c3c8f6b8) | Sep 06, 2025 |
| Dell          | Latitude E6420              | [af83dd94a5](https://linux-hardware.org/?probe=af83dd94a5) | Sep 06, 2025 |
| Dell          | Latitude E6420              | [4c1bda74d5](https://linux-hardware.org/?probe=4c1bda74d5) | Sep 04, 2025 |
| Dell          | Inspiron 5584               | [2c3427112f](https://linux-hardware.org/?probe=2c3427112f) | Sep 04, 2025 |
| System76      | Darter Pro                  | [ca35503054](https://linux-hardware.org/?probe=ca35503054) | Sep 03, 2025 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [e07bf31ecf](https://linux-hardware.org/?probe=e07bf31ecf) | Sep 03, 2025 |
| MSI           | Katana A15 AI B8VF          | [17ef7b7521](https://linux-hardware.org/?probe=17ef7b7521) | Sep 03, 2025 |
| HP            | ZBook 15                    | [8bd8e78e42](https://linux-hardware.org/?probe=8bd8e78e42) | Sep 02, 2025 |
| MSI           | GT72 6QD                    | [a47df5dd29](https://linux-hardware.org/?probe=a47df5dd29) | Sep 02, 2025 |
| Acer          | Nitro AN17-41               | [c26091e9d8](https://linux-hardware.org/?probe=c26091e9d8) | Sep 01, 2025 |
| Google        | Blooglet                    | [370390ad2f](https://linux-hardware.org/?probe=370390ad2f) | Sep 01, 2025 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | [25d3ade113](https://linux-hardware.org/?probe=25d3ade113) | Sep 01, 2025 |
| HP            | Laptop 14-dk1xxx            | [c31e78ba72](https://linux-hardware.org/?probe=c31e78ba72) | Sep 01, 2025 |
| Apple         | MacBookAir5,2               | [a767dab6a6](https://linux-hardware.org/?probe=a767dab6a6) | Aug 31, 2025 |
| HP            | Pavilion g7                 | [4ac250001b](https://linux-hardware.org/?probe=4ac250001b) | Aug 30, 2025 |
| Razer         | Blade                       | [cb98e123be](https://linux-hardware.org/?probe=cb98e123be) | Aug 30, 2025 |
| Dell          | Inspiron 5566               | [268a296123](https://linux-hardware.org/?probe=268a296123) | Aug 30, 2025 |
| System76      | Pangolin                    | [721dd30734](https://linux-hardware.org/?probe=721dd30734) | Aug 29, 2025 |
| Apple         | MacBookPro11,5              | [424d535907](https://linux-hardware.org/?probe=424d535907) | Aug 29, 2025 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [80e83bee7f](https://linux-hardware.org/?probe=80e83bee7f) | Aug 29, 2025 |
| Acer          | TravelMate 5760             | [1b5e622c00](https://linux-hardware.org/?probe=1b5e622c00) | Aug 29, 2025 |
| Apple         | MacBookAir7,2               | [732677a76f](https://linux-hardware.org/?probe=732677a76f) | Aug 29, 2025 |
| Apple         | MacBookPro11,2              | [b7ce67e63b](https://linux-hardware.org/?probe=b7ce67e63b) | Aug 29, 2025 |
| TongFang      | GX5MRXL                     | [e60a77d23d](https://linux-hardware.org/?probe=e60a77d23d) | Aug 27, 2025 |
| Lenovo        | IdeaPad 1 15IAU7 82VY       | [104f1ff19d](https://linux-hardware.org/?probe=104f1ff19d) | Aug 27, 2025 |
| Dell          | Vostro 3520                 | [3348304703](https://linux-hardware.org/?probe=3348304703) | Aug 27, 2025 |
| Lenovo        | ThinkPad Yoga 14 20FY000... | [8e35e58b46](https://linux-hardware.org/?probe=8e35e58b46) | Aug 27, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [151894ed32](https://linux-hardware.org/?probe=151894ed32) | Aug 27, 2025 |
| Lenovo        | Unknown                     | [6ddd3c5199](https://linux-hardware.org/?probe=6ddd3c5199) | Aug 26, 2025 |
| LG Electro... | 16Z90TP-K.ADL6U1            | [341b1299f0](https://linux-hardware.org/?probe=341b1299f0) | Aug 26, 2025 |
| System76      | Oryx Pro                    | [4eaaf90b5b](https://linux-hardware.org/?probe=4eaaf90b5b) | Aug 26, 2025 |
| Lenovo        | IdeaPad 1 15IAU7 82VY       | [f6a47466ad](https://linux-hardware.org/?probe=f6a47466ad) | Aug 25, 2025 |
| MSI           | Modern 14 C7M               | [798ffdf8f2](https://linux-hardware.org/?probe=798ffdf8f2) | Aug 25, 2025 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [30790b2256](https://linux-hardware.org/?probe=30790b2256) | Aug 25, 2025 |
| MSI           | Modern 14 B11MOU            | [400d26fa5d](https://linux-hardware.org/?probe=400d26fa5d) | Aug 25, 2025 |
| HP            | OMEN by Laptop 15-dh1xxx    | [3a4f0e662e](https://linux-hardware.org/?probe=3a4f0e662e) | Aug 25, 2025 |
| Acer          | Aspire V5-571G              | [d2155eeec3](https://linux-hardware.org/?probe=d2155eeec3) | Aug 25, 2025 |
| ASUSTek       | X555LPB                     | [ec0565afaf](https://linux-hardware.org/?probe=ec0565afaf) | Aug 25, 2025 |
| Lenovo        | V14 G3 IAP 82TS             | [b12d5ed99a](https://linux-hardware.org/?probe=b12d5ed99a) | Aug 24, 2025 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [0e8fa70a07](https://linux-hardware.org/?probe=0e8fa70a07) | Aug 24, 2025 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | [c1075d5215](https://linux-hardware.org/?probe=c1075d5215) | Aug 24, 2025 |
| Dell          | Latitude E6230              | [e5eda492e5](https://linux-hardware.org/?probe=e5eda492e5) | Aug 23, 2025 |
| Apple         | MacBookPro9,2               | [7e58a7f36f](https://linux-hardware.org/?probe=7e58a7f36f) | Aug 23, 2025 |
| HP            | ZBook 17 G3                 | [c7d807af40](https://linux-hardware.org/?probe=c7d807af40) | Aug 22, 2025 |
| HP            | ProBook 440 G2              | [6e73779cc7](https://linux-hardware.org/?probe=6e73779cc7) | Aug 22, 2025 |
| HP            | ProBook 440 G2              | [220639ed23](https://linux-hardware.org/?probe=220639ed23) | Aug 22, 2025 |
| Dell          | XPS 15 9560                 | [03edd91283](https://linux-hardware.org/?probe=03edd91283) | Aug 22, 2025 |
| Dell          | XPS 15 9560                 | [b829688f84](https://linux-hardware.org/?probe=b829688f84) | Aug 22, 2025 |
| HP            | Pavilion Sleekbook 14 PC    | [d9aa96ec2f](https://linux-hardware.org/?probe=d9aa96ec2f) | Aug 22, 2025 |
| HP            | Pavilion Sleekbook 14 PC    | [91b67e5ab5](https://linux-hardware.org/?probe=91b67e5ab5) | Aug 22, 2025 |
| Razer         | Blade 15 Advanced Model ... | [718ec76478](https://linux-hardware.org/?probe=718ec76478) | Aug 21, 2025 |
| PC Special... | Lafite Pro 15 AMD           | [8335776c4d](https://linux-hardware.org/?probe=8335776c4d) | Aug 21, 2025 |
| HP            | Presario C700 (GR582EA#A... | [4edf58541e](https://linux-hardware.org/?probe=4edf58541e) | Aug 21, 2025 |
| HP            | Presario C700 (GR582EA#A... | [4dfccf9cce](https://linux-hardware.org/?probe=4dfccf9cce) | Aug 21, 2025 |
| HP            | EliteBook 845 G7 Noteboo... | [c2a56b5473](https://linux-hardware.org/?probe=c2a56b5473) | Aug 21, 2025 |
| Apple         | MacBookAir6,2               | [e701852807](https://linux-hardware.org/?probe=e701852807) | Aug 21, 2025 |
| ASUSTek       | ASUS V16 V3607VH_V3607VH    | [e303b36082](https://linux-hardware.org/?probe=e303b36082) | Aug 19, 2025 |
| Apple         | MacBookPro15,1              | [a0b6141910](https://linux-hardware.org/?probe=a0b6141910) | Aug 19, 2025 |
| Acer          | Nitro AN515-58              | [2b78e0bc1b](https://linux-hardware.org/?probe=2b78e0bc1b) | Aug 19, 2025 |
| Apple         | MacBookPro15,1              | [95c6947017](https://linux-hardware.org/?probe=95c6947017) | Aug 18, 2025 |
| Dell          | XPS 15 9510                 | [e2a086b7d2](https://linux-hardware.org/?probe=e2a086b7d2) | Aug 18, 2025 |
| MSI           | GF63 Thin 10SC              | [2671e91beb](https://linux-hardware.org/?probe=2671e91beb) | Aug 17, 2025 |
| System76      | Darter Pro                  | [bc6a4cf761](https://linux-hardware.org/?probe=bc6a4cf761) | Aug 17, 2025 |
| HP            | Laptop 15s-eq1xxx           | [6d90f82ef6](https://linux-hardware.org/?probe=6d90f82ef6) | Aug 17, 2025 |
| HP            | Notebook                    | [d0697ecad0](https://linux-hardware.org/?probe=d0697ecad0) | Aug 17, 2025 |
| HP            | OMEN by Laptop 15-dh1xxx    | [e5c9e27d78](https://linux-hardware.org/?probe=e5c9e27d78) | Aug 16, 2025 |
| XIAOMI        | REDMI Book Pro 16 2025      | [dc1689517b](https://linux-hardware.org/?probe=dc1689517b) | Aug 16, 2025 |
| Alienware     | m17 R3                      | [91c06c76e7](https://linux-hardware.org/?probe=91c06c76e7) | Aug 16, 2025 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [e944e4073a](https://linux-hardware.org/?probe=e944e4073a) | Aug 16, 2025 |
| Dell          | Inspiron 15 7000 Gaming     | [200a08c26a](https://linux-hardware.org/?probe=200a08c26a) | Aug 15, 2025 |
| HUAWEI        | BOHB-WAX9                   | [09868d5e3f](https://linux-hardware.org/?probe=09868d5e3f) | Aug 15, 2025 |
| Alienware     | 17 R4                       | [c57541a7ff](https://linux-hardware.org/?probe=c57541a7ff) | Aug 15, 2025 |
| Acer          | TravelMate X3410-M          | [6477f885d2](https://linux-hardware.org/?probe=6477f885d2) | Aug 14, 2025 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [9be5a7e4be](https://linux-hardware.org/?probe=9be5a7e4be) | Aug 14, 2025 |
| System76      | Adder WS                    | [249b11879f](https://linux-hardware.org/?probe=249b11879f) | Aug 14, 2025 |
| HP            | 14                          | [034a9f9626](https://linux-hardware.org/?probe=034a9f9626) | Aug 13, 2025 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8d9c41f5ab](https://linux-hardware.org/?probe=8d9c41f5ab) | Aug 13, 2025 |
| Alienware     | 17 R4                       | [b96554dfcb](https://linux-hardware.org/?probe=b96554dfcb) | Aug 13, 2025 |
| Alienware     | 17 R4                       | [b46d9ab3d2](https://linux-hardware.org/?probe=b46d9ab3d2) | Aug 13, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [72ddde3f42](https://linux-hardware.org/?probe=72ddde3f42) | Aug 12, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [14c02ab82a](https://linux-hardware.org/?probe=14c02ab82a) | Aug 11, 2025 |
| Dell          | Latitude 7390               | [202fd58a5e](https://linux-hardware.org/?probe=202fd58a5e) | Aug 10, 2025 |
| Apple         | MacBookPro11,2              | [5da31d9e6d](https://linux-hardware.org/?probe=5da31d9e6d) | Aug 10, 2025 |
| Lenovo        | ThinkPad X280 20KESBL212    | [0318071c67](https://linux-hardware.org/?probe=0318071c67) | Aug 10, 2025 |
| HP            | ProBook 6560b               | [77aa5bcb5e](https://linux-hardware.org/?probe=77aa5bcb5e) | Aug 10, 2025 |
| Notebook      | NH5x_7xEDx,RCx,RDx          | [1f5411a102](https://linux-hardware.org/?probe=1f5411a102) | Aug 09, 2025 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [9d446f9ef6](https://linux-hardware.org/?probe=9d446f9ef6) | Aug 08, 2025 |
| System76      | Oryx Pro                    | [72f348aef6](https://linux-hardware.org/?probe=72f348aef6) | Aug 08, 2025 |
| Lenovo        | ThinkPad T420 423665U       | [5b31d29c0e](https://linux-hardware.org/?probe=5b31d29c0e) | Aug 07, 2025 |
| Lenovo        | IdeaPad Slim 5 16AKP10 8... | [c06d9c641f](https://linux-hardware.org/?probe=c06d9c641f) | Aug 07, 2025 |
| Acer          | Aspire V5-573G              | [512e07dc60](https://linux-hardware.org/?probe=512e07dc60) | Aug 07, 2025 |
| Apple         | MacBookPro11,3              | [6850526e05](https://linux-hardware.org/?probe=6850526e05) | Aug 05, 2025 |
| Acer          | Aspire A715-42G             | [b9fb93fc30](https://linux-hardware.org/?probe=b9fb93fc30) | Aug 05, 2025 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [0b023054b7](https://linux-hardware.org/?probe=0b023054b7) | Aug 04, 2025 |
| INFINITY      | XQ6-8R7R6A (23)             | [0df5c7eedd](https://linux-hardware.org/?probe=0df5c7eedd) | Aug 01, 2025 |
| Dell          | Inspiron 7460               | [c3b9bf3647](https://linux-hardware.org/?probe=c3b9bf3647) | Aug 01, 2025 |
| HP            | Notebook                    | [77c2a3f00b](https://linux-hardware.org/?probe=77c2a3f00b) | Jul 30, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [bb1f15107f](https://linux-hardware.org/?probe=bb1f15107f) | Jul 30, 2025 |
| Lenovo        | Legion 7 16IRX9 83FD        | [62bbfe3580](https://linux-hardware.org/?probe=62bbfe3580) | Jul 30, 2025 |
| Acer          | Nitro AN515-45              | [70ef8f6a66](https://linux-hardware.org/?probe=70ef8f6a66) | Jul 29, 2025 |
| MSI           | GS60 6QE                    | [f70e9b17a9](https://linux-hardware.org/?probe=f70e9b17a9) | Jul 28, 2025 |
| Lenovo        | ThinkPad E595 20NF001HMX    | [a62a6e5f84](https://linux-hardware.org/?probe=a62a6e5f84) | Jul 27, 2025 |
| Lenovo        | ThinkPad T560 20FHCTO1WW    | [f4058f7b13](https://linux-hardware.org/?probe=f4058f7b13) | Jul 27, 2025 |
| Acer          | Aspire A514-54              | [5d27d3738c](https://linux-hardware.org/?probe=5d27d3738c) | Jul 27, 2025 |
| Notebook      | X370SNx                     | [b54541d50a](https://linux-hardware.org/?probe=b54541d50a) | Jul 27, 2025 |
| Framework     | Laptop                      | [ebaf6ceeeb](https://linux-hardware.org/?probe=ebaf6ceeeb) | Jul 26, 2025 |
| Dell          | Vostro 3700                 | [b3133e04c0](https://linux-hardware.org/?probe=b3133e04c0) | Jul 26, 2025 |
| ASUSTek       | ASUS V16 V3607VH_V3607VH    | [260393025d](https://linux-hardware.org/?probe=260393025d) | Jul 25, 2025 |
| System76      | Darter Pro                  | [25f8f54f0e](https://linux-hardware.org/?probe=25f8f54f0e) | Jul 24, 2025 |
| Acer          | Predator PH315-52           | [56b22a8441](https://linux-hardware.org/?probe=56b22a8441) | Jul 24, 2025 |
| Lenovo        | LOQ 15APH8 82XT             | [3385358c83](https://linux-hardware.org/?probe=3385358c83) | Jul 24, 2025 |
| HP            | OMEN by Gaming Laptop 16... | [e24a340eba](https://linux-hardware.org/?probe=e24a340eba) | Jul 23, 2025 |
| ASUSTek       | N551JW                      | [a109c986a8](https://linux-hardware.org/?probe=a109c986a8) | Jul 23, 2025 |
| HP            | Victus by Laptop 16-d0xx... | [fec0d03b43](https://linux-hardware.org/?probe=fec0d03b43) | Jul 22, 2025 |
| Apple         | MacBookPro15,1              | [1650970366](https://linux-hardware.org/?probe=1650970366) | Jul 22, 2025 |
| HP            | ProBook 430 G8 Notebook ... | [ffd1782bf3](https://linux-hardware.org/?probe=ffd1782bf3) | Jul 22, 2025 |
| MSI           | PS63 Modern 8RC             | [3877ff4481](https://linux-hardware.org/?probe=3877ff4481) | Jul 22, 2025 |
| Lenovo        | Yoga Slim 7 14AKP10 83JY    | [b45c559c30](https://linux-hardware.org/?probe=b45c559c30) | Jul 21, 2025 |
| Casper        | NIRVANA NB F500             | [7d0398ec28](https://linux-hardware.org/?probe=7d0398ec28) | Jul 21, 2025 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [2ab94639cc](https://linux-hardware.org/?probe=2ab94639cc) | Jul 21, 2025 |
| Alienware     | m17 R5 AMD                  | [2895503f07](https://linux-hardware.org/?probe=2895503f07) | Jul 21, 2025 |
| ASUSTek       | N73SV                       | [26d04a5e60](https://linux-hardware.org/?probe=26d04a5e60) | Jul 21, 2025 |
| MSI           | PS63 Modern 8RC             | [76cfa037ae](https://linux-hardware.org/?probe=76cfa037ae) | Jul 20, 2025 |
| Lenovo        | ThinkPad X250 20CLS69S00    | [601e123879](https://linux-hardware.org/?probe=601e123879) | Jul 20, 2025 |
| Medion        | P6681 MD60677               | [8d7f19ce6f](https://linux-hardware.org/?probe=8d7f19ce6f) | Jul 19, 2025 |
| ASUSTek       | GL752VW                     | [9648d71d87](https://linux-hardware.org/?probe=9648d71d87) | Jul 19, 2025 |
| System76      | Pangolin                    | [82f10c8289](https://linux-hardware.org/?probe=82f10c8289) | Jul 19, 2025 |
| System76      | Oryx Pro                    | [56cfecb33a](https://linux-hardware.org/?probe=56cfecb33a) | Jul 18, 2025 |
| Dell          | XPS 13 9300                 | [7076a0208c](https://linux-hardware.org/?probe=7076a0208c) | Jul 18, 2025 |
| ASUSTek       | ASUS TUF Gaming F16 FX60... | [ac22e2b602](https://linux-hardware.org/?probe=ac22e2b602) | Jul 18, 2025 |
| Apple         | MacBookPro12,1              | [22417496f0](https://linux-hardware.org/?probe=22417496f0) | Jul 18, 2025 |
| ASUSTek       | ASUS Vivobook S 14 S5406... | [95b3156df3](https://linux-hardware.org/?probe=95b3156df3) | Jul 18, 2025 |
| Gigabyte      | G6X9KG                      | [aafba91e05](https://linux-hardware.org/?probe=aafba91e05) | Jul 18, 2025 |
| ASUSTek       | G74Sx                       | [08c3f13e37](https://linux-hardware.org/?probe=08c3f13e37) | Jul 17, 2025 |
| ASUSTek       | G74Sx                       | [059091c1e5](https://linux-hardware.org/?probe=059091c1e5) | Jul 17, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [a085f23042](https://linux-hardware.org/?probe=a085f23042) | Jul 17, 2025 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [18e0374597](https://linux-hardware.org/?probe=18e0374597) | Jul 16, 2025 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [0145ce930d](https://linux-hardware.org/?probe=0145ce930d) | Jul 16, 2025 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [efae1c3685](https://linux-hardware.org/?probe=efae1c3685) | Jul 15, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [f19364cf20](https://linux-hardware.org/?probe=f19364cf20) | Jul 15, 2025 |
| Alienware     | m17 R3                      | [58b1b6711b](https://linux-hardware.org/?probe=58b1b6711b) | Jul 15, 2025 |
| Lenovo        | ThinkPad E14 Gen 5 21JRS... | [2e740c60e5](https://linux-hardware.org/?probe=2e740c60e5) | Jul 15, 2025 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | [08a7b13aed](https://linux-hardware.org/?probe=08a7b13aed) | Jul 15, 2025 |
| Lenovo        | Legion 5 15IMH05 82AU       | [f0ea99968a](https://linux-hardware.org/?probe=f0ea99968a) | Jul 14, 2025 |
| Acer          | Nitro AN517-52              | [c83be66cef](https://linux-hardware.org/?probe=c83be66cef) | Jul 13, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c83e2d2bd7](https://linux-hardware.org/?probe=c83e2d2bd7) | Jul 13, 2025 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [b53ccd6ffe](https://linux-hardware.org/?probe=b53ccd6ffe) | Jul 13, 2025 |
| ASUSTek       | K46CB                       | [e9226d5b99](https://linux-hardware.org/?probe=e9226d5b99) | Jul 12, 2025 |
| MSI           | GT62VR 7RE                  | [61c719f58e](https://linux-hardware.org/?probe=61c719f58e) | Jul 11, 2025 |
| ASUSTek       | K46CB                       | [48d2659871](https://linux-hardware.org/?probe=48d2659871) | Jul 11, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [96723c7b16](https://linux-hardware.org/?probe=96723c7b16) | Jul 11, 2025 |
| Acer          | Nitro AN515-54              | [dfa02e27a8](https://linux-hardware.org/?probe=dfa02e27a8) | Jul 11, 2025 |
| Acer          | Nitro AN515-54              | [f79d1fae4b](https://linux-hardware.org/?probe=f79d1fae4b) | Jul 11, 2025 |
| HP            | Victus by Gaming Laptop ... | [31e1efebc3](https://linux-hardware.org/?probe=31e1efebc3) | Jul 10, 2025 |
| Apple         | MacBook8,1                  | [e02361fb60](https://linux-hardware.org/?probe=e02361fb60) | Jul 10, 2025 |
| HP            | EliteBook 845 G8 Noteboo... | [d7c9a1a7e5](https://linux-hardware.org/?probe=d7c9a1a7e5) | Jul 10, 2025 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [f01c6cb572](https://linux-hardware.org/?probe=f01c6cb572) | Jul 10, 2025 |
| System76      | Darter Pro                  | [17726b23c3](https://linux-hardware.org/?probe=17726b23c3) | Jul 09, 2025 |
| System76      | Pangolin                    | [2afc0f81c8](https://linux-hardware.org/?probe=2afc0f81c8) | Jul 09, 2025 |
| Infinix       | ZERO BOOK 13                | [f6533aa1d8](https://linux-hardware.org/?probe=f6533aa1d8) | Jul 09, 2025 |
| HP            | Unknown                     | [1b41e6e58c](https://linux-hardware.org/?probe=1b41e6e58c) | Jul 09, 2025 |
| Medion        | Deputy P60i                 | [871329b6ca](https://linux-hardware.org/?probe=871329b6ca) | Jul 08, 2025 |
| Medion        | Deputy P60i                 | [fb2e0ca039](https://linux-hardware.org/?probe=fb2e0ca039) | Jul 08, 2025 |
| HP            | Unknown                     | [4325dc6f7a](https://linux-hardware.org/?probe=4325dc6f7a) | Jul 08, 2025 |
| MSI           | Thin A15 B7VF               | [8af882ca47](https://linux-hardware.org/?probe=8af882ca47) | Jul 08, 2025 |
| MSI           | Thin A15 B7VF               | [03b32ca9e7](https://linux-hardware.org/?probe=03b32ca9e7) | Jul 08, 2025 |
| Lenovo        | ThinkPad T470s 20HFCT01W... | [ce440d731d](https://linux-hardware.org/?probe=ce440d731d) | Jul 07, 2025 |
| Acer          | Aspire E5-575G              | [c284d077ae](https://linux-hardware.org/?probe=c284d077ae) | Jul 07, 2025 |
| Compaq(Int... | Unknown                     | [70258d60d8](https://linux-hardware.org/?probe=70258d60d8) | Jul 06, 2025 |
| Lenovo        | ThinkPad P53 20QQS3831M     | [27339875ca](https://linux-hardware.org/?probe=27339875ca) | Jul 06, 2025 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [2d1183d668](https://linux-hardware.org/?probe=2d1183d668) | Jul 05, 2025 |
| Acer          | Swift SF514-52T             | [48f0d10ad2](https://linux-hardware.org/?probe=48f0d10ad2) | Jul 05, 2025 |
| Digma         | Pro Fortis M DN15P3-8DXW... | [e6a59f1384](https://linux-hardware.org/?probe=e6a59f1384) | Jul 05, 2025 |
| MSI           | MPG B550 GAMING PLUS        | [de632aeb8a](https://linux-hardware.org/?probe=de632aeb8a) | Jul 05, 2025 |
| System76      | Galago Pro                  | [e70c206a7d](https://linux-hardware.org/?probe=e70c206a7d) | Jul 04, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [70129e8fc8](https://linux-hardware.org/?probe=70129e8fc8) | Jul 04, 2025 |
| ASUSTek       | GL552VX                     | [6c6bba2b66](https://linux-hardware.org/?probe=6c6bba2b66) | Jul 04, 2025 |
| Apple         | MacBook8,1                  | [d22f167253](https://linux-hardware.org/?probe=d22f167253) | Jul 04, 2025 |
| Lenovo        | ThinkPad T14s Gen 6 21M2... | [4e306d5d35](https://linux-hardware.org/?probe=4e306d5d35) | Jul 04, 2025 |
| Alienware     | m15 R7                      | [491252bd51](https://linux-hardware.org/?probe=491252bd51) | Jul 04, 2025 |
| HP            | OMEN by Transcend Gaming... | [6113974d9f](https://linux-hardware.org/?probe=6113974d9f) | Jul 03, 2025 |
| Dell          | Latitude E6530              | [53d5baa731](https://linux-hardware.org/?probe=53d5baa731) | Jul 03, 2025 |
| HP            | Pavilion Laptop 15-cd0xx    | [16bd0fbadd](https://linux-hardware.org/?probe=16bd0fbadd) | Jul 03, 2025 |
| Dell          | Latitude E6330              | [0ba2c3c247](https://linux-hardware.org/?probe=0ba2c3c247) | Jul 03, 2025 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | [4431563903](https://linux-hardware.org/?probe=4431563903) | Jul 02, 2025 |
| ASUSTek       | ROG Strix G513IE_G513IE     | [897908d2d5](https://linux-hardware.org/?probe=897908d2d5) | Jul 02, 2025 |
| ASUSTek       | N501VW                      | [49f3584d20](https://linux-hardware.org/?probe=49f3584d20) | Jul 01, 2025 |
| ASUSTek       | N501VW                      | [0bd13c5a26](https://linux-hardware.org/?probe=0bd13c5a26) | Jul 01, 2025 |
| HUAWEI        | MCLG-XX                     | [d8a9fae03f](https://linux-hardware.org/?probe=d8a9fae03f) | Jul 01, 2025 |
| Apple         | MacBook8,1                  | [8f3272c2e6](https://linux-hardware.org/?probe=8f3272c2e6) | Jul 01, 2025 |
| Acer          | Nitro ANV15-51              | [5d53d398ce](https://linux-hardware.org/?probe=5d53d398ce) | Jun 30, 2025 |
| Acer          | Nitro ANV15-51              | [9f77deebdd](https://linux-hardware.org/?probe=9f77deebdd) | Jun 30, 2025 |
| ASUSTek       | K53SC                       | [ca635bc519](https://linux-hardware.org/?probe=ca635bc519) | Jun 30, 2025 |
| System76      | Pangolin                    | [7aadbc0b69](https://linux-hardware.org/?probe=7aadbc0b69) | Jun 30, 2025 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | [4e935baf45](https://linux-hardware.org/?probe=4e935baf45) | Jun 29, 2025 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | [5ade9a71de](https://linux-hardware.org/?probe=5ade9a71de) | Jun 29, 2025 |
| MOTILE        | M142                        | [0747de105b](https://linux-hardware.org/?probe=0747de105b) | Jun 29, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [e403befcb5](https://linux-hardware.org/?probe=e403befcb5) | Jun 29, 2025 |
| HP            | ProBook 640 G4              | [edd64bc616](https://linux-hardware.org/?probe=edd64bc616) | Jun 28, 2025 |
| Acer          | Swift SF314-57              | [464bfc5796](https://linux-hardware.org/?probe=464bfc5796) | Jun 28, 2025 |
| Dell          | Latitude 5590               | [3e0ecf8c1b](https://linux-hardware.org/?probe=3e0ecf8c1b) | Jun 28, 2025 |
| Positivo      | CI38256GBW10                | [84afcc376a](https://linux-hardware.org/?probe=84afcc376a) | Jun 28, 2025 |
| Lenovo        | Y520-15IKBN 80WK            | [d0d5274050](https://linux-hardware.org/?probe=d0d5274050) | Jun 27, 2025 |
| MSI           | Prestige 16Studio A13VF     | [c80c700709](https://linux-hardware.org/?probe=c80c700709) | Jun 26, 2025 |
| LG Electro... | R590-P.BE54P1               | [f52d3ffb66](https://linux-hardware.org/?probe=f52d3ffb66) | Jun 26, 2025 |
| LG Electro... | R590-P.BE54P1               | [d36cc7d165](https://linux-hardware.org/?probe=d36cc7d165) | Jun 26, 2025 |
| HUAWEI        | BOD-WXX9                    | [a5e1d340f3](https://linux-hardware.org/?probe=a5e1d340f3) | Jun 26, 2025 |
| Acer          | Aspire 5738                 | [7b0ee1cba4](https://linux-hardware.org/?probe=7b0ee1cba4) | Jun 26, 2025 |
| Lenovo        | Y520-15IKBN 80WK            | [35c922cd18](https://linux-hardware.org/?probe=35c922cd18) | Jun 25, 2025 |
| Standard      | Unknown                     | [b92f7876b4](https://linux-hardware.org/?probe=b92f7876b4) | Jun 25, 2025 |
| ASUSTek       | G74Sx                       | [952afcce17](https://linux-hardware.org/?probe=952afcce17) | Jun 24, 2025 |
| Acer          | Aspire VN7-592G             | [ae150597c7](https://linux-hardware.org/?probe=ae150597c7) | Jun 24, 2025 |
| HP            | Dragonfly Pro Laptop PC     | [1f7946197c](https://linux-hardware.org/?probe=1f7946197c) | Jun 24, 2025 |
| Lenovo        | ThinkPad T470s 20HFCT01W... | [8bb362b28e](https://linux-hardware.org/?probe=8bb362b28e) | Jun 24, 2025 |
| Acer          | Aspire A14-52M              | [ed8dfd78a5](https://linux-hardware.org/?probe=ed8dfd78a5) | Jun 23, 2025 |
| Apple         | MacBookAir7,2               | [b9ca9ce9aa](https://linux-hardware.org/?probe=b9ca9ce9aa) | Jun 23, 2025 |
| HP            | Pavilion Gaming Laptop 1... | [291faf05bc](https://linux-hardware.org/?probe=291faf05bc) | Jun 23, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [856ec752ea](https://linux-hardware.org/?probe=856ec752ea) | Jun 22, 2025 |
| Dell          | XPS 13 9360                 | [b165b7cd23](https://linux-hardware.org/?probe=b165b7cd23) | Jun 21, 2025 |
| Lenovo        | IdeaPad S340-14API 81NB     | [56bf68ba81](https://linux-hardware.org/?probe=56bf68ba81) | Jun 21, 2025 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [f462643005](https://linux-hardware.org/?probe=f462643005) | Jun 21, 2025 |
| Lenovo        | IdeaPad S340-15API 81NC     | [fb5dae8293](https://linux-hardware.org/?probe=fb5dae8293) | Jun 21, 2025 |
| HP            | Pavilion Plus Laptop 14-... | [3e66b84454](https://linux-hardware.org/?probe=3e66b84454) | Jun 21, 2025 |
| MSI           | Katana GF76 12UGS           | [1f0df83186](https://linux-hardware.org/?probe=1f0df83186) | Jun 21, 2025 |
| HP            | Pavilion Gaming Laptop 1... | [754192704e](https://linux-hardware.org/?probe=754192704e) | Jun 20, 2025 |
| Dell          | Precision 3530              | [d618b22c67](https://linux-hardware.org/?probe=d618b22c67) | Jun 20, 2025 |
| HP            | ENVY 17                     | [360dda0e39](https://linux-hardware.org/?probe=360dda0e39) | Jun 20, 2025 |
| HP            | ENVY 17                     | [08dff225d2](https://linux-hardware.org/?probe=08dff225d2) | Jun 20, 2025 |
| MSI           | GS76 Stealth 11UH           | [3bae8ae406](https://linux-hardware.org/?probe=3bae8ae406) | Jun 20, 2025 |
| Dell          | Latitude D630               | [8804afbc73](https://linux-hardware.org/?probe=8804afbc73) | Jun 20, 2025 |
| Apple         | MacBook5,1                  | [ceb308df54](https://linux-hardware.org/?probe=ceb308df54) | Jun 19, 2025 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [ac61963cb0](https://linux-hardware.org/?probe=ac61963cb0) | Jun 18, 2025 |
| Samsung       | 300E5E/300E4E/300E5V/300... | [05f5bd0171](https://linux-hardware.org/?probe=05f5bd0171) | Jun 18, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c6a728b131](https://linux-hardware.org/?probe=c6a728b131) | Jun 17, 2025 |
| System76      | Darter Pro                  | [5ca8b470c6](https://linux-hardware.org/?probe=5ca8b470c6) | Jun 17, 2025 |
| Dell          | Precision 3591              | [5ee399a2f1](https://linux-hardware.org/?probe=5ee399a2f1) | Jun 17, 2025 |
| TongFang      | GX5MRXL                     | [5740fc59cd](https://linux-hardware.org/?probe=5740fc59cd) | Jun 16, 2025 |
| HP            | Pavilion Gaming Laptop 1... | [0ddb6daba2](https://linux-hardware.org/?probe=0ddb6daba2) | Jun 16, 2025 |
| HP            | Pavilion Gaming Laptop 1... | [e50f0d4fc3](https://linux-hardware.org/?probe=e50f0d4fc3) | Jun 16, 2025 |
| Lenovo        | ThinkPad P1 Gen 7 21KV00... | [5bb9dd8c62](https://linux-hardware.org/?probe=5bb9dd8c62) | Jun 16, 2025 |
| HP            | 15                          | [83f13ac2e0](https://linux-hardware.org/?probe=83f13ac2e0) | Jun 16, 2025 |
| MSI           | GS70 2PC Stealth            | [bcc741566b](https://linux-hardware.org/?probe=bcc741566b) | Jun 16, 2025 |
| Dell          | XPS 15 9570                 | [1c26dab19b](https://linux-hardware.org/?probe=1c26dab19b) | Jun 15, 2025 |
| Dell          | Inspiron 1525               | [bc8cf2a4de](https://linux-hardware.org/?probe=bc8cf2a4de) | Jun 15, 2025 |
| Dell          | Inspiron 1525               | [94a7724f6a](https://linux-hardware.org/?probe=94a7724f6a) | Jun 15, 2025 |
| HP            | Pavilion Gaming Laptop 1... | [7abf7c1d5b](https://linux-hardware.org/?probe=7abf7c1d5b) | Jun 15, 2025 |
| MSI           | GF63 Thin 10SCXR            | [cbf652d529](https://linux-hardware.org/?probe=cbf652d529) | Jun 14, 2025 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [c8eb984098](https://linux-hardware.org/?probe=c8eb984098) | Jun 13, 2025 |
| ASUSTek       | P552LA                      | [c3240548cd](https://linux-hardware.org/?probe=c3240548cd) | Jun 13, 2025 |
| ASUSTek       | P552LA                      | [4a461e497b](https://linux-hardware.org/?probe=4a461e497b) | Jun 13, 2025 |
| Dell          | XPS 15 9500                 | [2bc09a8e15](https://linux-hardware.org/?probe=2bc09a8e15) | Jun 13, 2025 |
| Dell          | Precision 5520              | [b191cdb6c9](https://linux-hardware.org/?probe=b191cdb6c9) | Jun 13, 2025 |
| MSI           | GL65 Leopard 10SER          | [110eac6315](https://linux-hardware.org/?probe=110eac6315) | Jun 12, 2025 |
| Dell          | Latitude 3540               | [36bd5d2724](https://linux-hardware.org/?probe=36bd5d2724) | Jun 12, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [020a315574](https://linux-hardware.org/?probe=020a315574) | Jun 11, 2025 |
| Dell          | Precision 3591              | [886855260a](https://linux-hardware.org/?probe=886855260a) | Jun 11, 2025 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [3d461b1067](https://linux-hardware.org/?probe=3d461b1067) | Jun 11, 2025 |
| System76      | Gazelle                     | [a43a5e4d45](https://linux-hardware.org/?probe=a43a5e4d45) | Jun 11, 2025 |
| Dell          | Latitude E6330              | [1f904bdc3d](https://linux-hardware.org/?probe=1f904bdc3d) | Jun 11, 2025 |
| Toshiba       | Satellite C850-F31Q         | [c5b61196a3](https://linux-hardware.org/?probe=c5b61196a3) | Jun 10, 2025 |
| HP            | Laptop 15-db0xxx            | [b2a94c804c](https://linux-hardware.org/?probe=b2a94c804c) | Jun 10, 2025 |
| HP            | Victus by Gaming Laptop ... | [04ea93d7bf](https://linux-hardware.org/?probe=04ea93d7bf) | Jun 10, 2025 |
| HP            | Victus by Gaming Laptop ... | [e5db167b7f](https://linux-hardware.org/?probe=e5db167b7f) | Jun 10, 2025 |
| Dell          | Inspiron 5584               | [41cfaa2565](https://linux-hardware.org/?probe=41cfaa2565) | Jun 09, 2025 |
| Lenovo        | ThinkPad T480 20L6S03X00    | [213327a2e0](https://linux-hardware.org/?probe=213327a2e0) | Jun 09, 2025 |
| ASUSTek       | ProArt Studiobook W7600Z... | [c32df33cb2](https://linux-hardware.org/?probe=c32df33cb2) | Jun 09, 2025 |
| Lenovo        | LOQ 15AHP9 83DX             | [3b799ab6bf](https://linux-hardware.org/?probe=3b799ab6bf) | Jun 09, 2025 |
| Lenovo        | Legion Y530-15ICH 81FV      | [7276797749](https://linux-hardware.org/?probe=7276797749) | Jun 09, 2025 |
| MSI           | GP72M 7REX                  | [ecc6666f3d](https://linux-hardware.org/?probe=ecc6666f3d) | Jun 09, 2025 |
| Lenovo        | Unknown                     | [7e9d0d7765](https://linux-hardware.org/?probe=7e9d0d7765) | Jun 09, 2025 |
| Dell          | Inspiron 5584               | [018448ec6d](https://linux-hardware.org/?probe=018448ec6d) | Jun 09, 2025 |
| Lenovo        | ThinkPad P53 20QQS3831M     | [34665aebd4](https://linux-hardware.org/?probe=34665aebd4) | Jun 08, 2025 |
| Timi          | Xiaomi NoteBook Pro         | [6ac6fb5a53](https://linux-hardware.org/?probe=6ac6fb5a53) | Jun 08, 2025 |
| Chuwi         | LapBook Plus                | [6af3892713](https://linux-hardware.org/?probe=6af3892713) | Jun 07, 2025 |
| MSI           | Vector 17 HX A14VIG         | [bf2a9334fa](https://linux-hardware.org/?probe=bf2a9334fa) | Jun 06, 2025 |
| Alienware     | m16 R1                      | [7090318af2](https://linux-hardware.org/?probe=7090318af2) | Jun 06, 2025 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [420bcdc2da](https://linux-hardware.org/?probe=420bcdc2da) | Jun 05, 2025 |
| Lenovo        | ThinkPad L450 20DSS17N00    | [789d2d0302](https://linux-hardware.org/?probe=789d2d0302) | Jun 05, 2025 |
| Metabox       | Flo L140AU                  | [1d19f0ee35](https://linux-hardware.org/?probe=1d19f0ee35) | Jun 05, 2025 |
| Acer          | Nitro ANV15-51              | [593a8149ea](https://linux-hardware.org/?probe=593a8149ea) | Jun 05, 2025 |
| Lenovo        | V145-15AST 81MT             | [b06e73acf7](https://linux-hardware.org/?probe=b06e73acf7) | Jun 05, 2025 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [5a93b6641c](https://linux-hardware.org/?probe=5a93b6641c) | Jun 04, 2025 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [8e48e2da7f](https://linux-hardware.org/?probe=8e48e2da7f) | Jun 04, 2025 |
| Apple         | MacBookPro11,1              | [53ac9ab67c](https://linux-hardware.org/?probe=53ac9ab67c) | Jun 04, 2025 |
| Dell          | Venue 11 Pro 7140           | [5368020290](https://linux-hardware.org/?probe=5368020290) | Jun 04, 2025 |
| Dell          | Latitude 5401               | [63bcc6b194](https://linux-hardware.org/?probe=63bcc6b194) | Jun 03, 2025 |
| Lenovo        | ThinkPad E14 Gen 6 21M30... | [d589daa890](https://linux-hardware.org/?probe=d589daa890) | Jun 03, 2025 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [269e9fec09](https://linux-hardware.org/?probe=269e9fec09) | Jun 03, 2025 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [e9ada5bd1a](https://linux-hardware.org/?probe=e9ada5bd1a) | Jun 03, 2025 |
| Apple         | MacBookAir8,1               | [dafcf26cee](https://linux-hardware.org/?probe=dafcf26cee) | Jun 02, 2025 |
| Dell          | Vostro 3500                 | [f2e1fe619b](https://linux-hardware.org/?probe=f2e1fe619b) | Jun 01, 2025 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [ef413831da](https://linux-hardware.org/?probe=ef413831da) | Jun 01, 2025 |
| Valve         | Jupiter                     | [214e129333](https://linux-hardware.org/?probe=214e129333) | Jun 01, 2025 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [587d0e9a7b](https://linux-hardware.org/?probe=587d0e9a7b) | Jun 01, 2025 |
| Apple         | MacBookPro11,1              | [fbcd2dfff6](https://linux-hardware.org/?probe=fbcd2dfff6) | May 31, 2025 |
| MECHREVO      | WUJIE14 PRO                 | [2eddf95511](https://linux-hardware.org/?probe=2eddf95511) | May 31, 2025 |
| Apple         | MacBookPro11,4              | [72c190a240](https://linux-hardware.org/?probe=72c190a240) | May 31, 2025 |
| MSI           | MS-7C04                     | [b792d72ef6](https://linux-hardware.org/?probe=b792d72ef6) | May 31, 2025 |
| Lenovo        | ThinkPad X280 20KESBL212    | [95ff6874c8](https://linux-hardware.org/?probe=95ff6874c8) | May 31, 2025 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [24fe361240](https://linux-hardware.org/?probe=24fe361240) | May 30, 2025 |
| HP            | EliteBook 850 G3            | [2e296c7d5d](https://linux-hardware.org/?probe=2e296c7d5d) | May 30, 2025 |
| Unknown       | Unknown                     | [a1d3abe494](https://linux-hardware.org/?probe=a1d3abe494) | May 29, 2025 |
| ASUSTek       | X556UQK                     | [51115aa946](https://linux-hardware.org/?probe=51115aa946) | May 29, 2025 |
| Unknown       | Unknown                     | [3e7b7b2345](https://linux-hardware.org/?probe=3e7b7b2345) | May 28, 2025 |
| Dell          | Vostro 5301                 | [16dea8f26a](https://linux-hardware.org/?probe=16dea8f26a) | May 28, 2025 |
| Google        | Osiris                      | [efb2a1a147](https://linux-hardware.org/?probe=efb2a1a147) | May 28, 2025 |
| ASUSTek       | X555LF                      | [9d92fe2c2b](https://linux-hardware.org/?probe=9d92fe2c2b) | May 28, 2025 |
| HP            | Pavilion Sleekbook 14 PC    | [c1f428373d](https://linux-hardware.org/?probe=c1f428373d) | May 28, 2025 |
| TongFang      | GX5MRXL                     | [32383d7d05](https://linux-hardware.org/?probe=32383d7d05) | May 27, 2025 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [c76bbfb5a1](https://linux-hardware.org/?probe=c76bbfb5a1) | May 27, 2025 |
| Lenovo        | ThinkPad T480 20L6S7K10A    | [380e41127d](https://linux-hardware.org/?probe=380e41127d) | May 27, 2025 |
| Dell          | Latitude E7240              | [a9e599536c](https://linux-hardware.org/?probe=a9e599536c) | May 27, 2025 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | [903fa1ce34](https://linux-hardware.org/?probe=903fa1ce34) | May 27, 2025 |
| Google        | Osiris                      | [ce815391fe](https://linux-hardware.org/?probe=ce815391fe) | May 27, 2025 |
| HP            | Pavilion 17                 | [c8f62e99c1](https://linux-hardware.org/?probe=c8f62e99c1) | May 27, 2025 |
| ASUSTek       | G75VX                       | [f9fd7c56ed](https://linux-hardware.org/?probe=f9fd7c56ed) | May 27, 2025 |
| System76      | Serval WS                   | [a58de16c1a](https://linux-hardware.org/?probe=a58de16c1a) | May 27, 2025 |
| Lenovo        | ThinkPad T480 20L6S6WQ00    | [3a94729ddd](https://linux-hardware.org/?probe=3a94729ddd) | May 27, 2025 |
| Lenovo        | ThinkPad T480 20L6S6WQ00    | [b57b9af820](https://linux-hardware.org/?probe=b57b9af820) | May 27, 2025 |
| System76      | Adder WS                    | [600e1b80cf](https://linux-hardware.org/?probe=600e1b80cf) | May 25, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [8057a11a98](https://linux-hardware.org/?probe=8057a11a98) | May 25, 2025 |
| MSI           | Creator M16 B13VE           | [40909ae472](https://linux-hardware.org/?probe=40909ae472) | May 25, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [d844d1244e](https://linux-hardware.org/?probe=d844d1244e) | May 25, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [ea22ca86b5](https://linux-hardware.org/?probe=ea22ca86b5) | May 25, 2025 |
| HP            | Laptop 14s-cf2xxx           | [9cc98bf67c](https://linux-hardware.org/?probe=9cc98bf67c) | May 24, 2025 |
| Dell          | XPS 13 9370                 | [dc87251713](https://linux-hardware.org/?probe=dc87251713) | May 24, 2025 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [fdeb3fc2f9](https://linux-hardware.org/?probe=fdeb3fc2f9) | May 23, 2025 |
| ASUSTek       | X555LAB                     | [3566904e95](https://linux-hardware.org/?probe=3566904e95) | May 23, 2025 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [04ce62a75b](https://linux-hardware.org/?probe=04ce62a75b) | May 23, 2025 |
| Acer          | Predator PT316-51s          | [f3a0f26602](https://linux-hardware.org/?probe=f3a0f26602) | May 22, 2025 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [cc717a0224](https://linux-hardware.org/?probe=cc717a0224) | May 22, 2025 |
| Fujitsu       | CELSIUS H730                | [d643867cfb](https://linux-hardware.org/?probe=d643867cfb) | May 22, 2025 |
| Apple         | MacBook5,1                  | [751943b073](https://linux-hardware.org/?probe=751943b073) | May 22, 2025 |
| HP            | Dragonfly Pro Laptop PC     | [0d7d676122](https://linux-hardware.org/?probe=0d7d676122) | May 22, 2025 |
| ASUSTek       | X555LAB                     | [e78de1353a](https://linux-hardware.org/?probe=e78de1353a) | May 22, 2025 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [804b538ddd](https://linux-hardware.org/?probe=804b538ddd) | May 21, 2025 |
| Acer          | Aspire 5741G                | [42ed2de824](https://linux-hardware.org/?probe=42ed2de824) | May 21, 2025 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [2e039c9628](https://linux-hardware.org/?probe=2e039c9628) | May 20, 2025 |
| System76      | Lemur Pro                   | [56e3711a39](https://linux-hardware.org/?probe=56e3711a39) | May 20, 2025 |
| ASUSTek       | ROG Strix G16 G614JVR_G6... | [fe7269558f](https://linux-hardware.org/?probe=fe7269558f) | May 20, 2025 |
| Lenovo        | ThinkPad T480 20L6S03X00    | [2db012da4e](https://linux-hardware.org/?probe=2db012da4e) | May 19, 2025 |
| HP            | EliteBook 845 G8 Noteboo... | [0093eac096](https://linux-hardware.org/?probe=0093eac096) | May 19, 2025 |
| HP            | OMEN by Laptop 17-ck2xxx    | [785f22df00](https://linux-hardware.org/?probe=785f22df00) | May 19, 2025 |
| Dell          | G7 7588                     | [f4e2c778f5](https://linux-hardware.org/?probe=f4e2c778f5) | May 19, 2025 |
| HP            | Laptop 15-bs0xx             | [e6fa2b079a](https://linux-hardware.org/?probe=e6fa2b079a) | May 18, 2025 |
| HP            | Presario V3000 (RD545PA#... | [f413204098](https://linux-hardware.org/?probe=f413204098) | May 18, 2025 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [c291f7da79](https://linux-hardware.org/?probe=c291f7da79) | May 18, 2025 |
| ASUSTek       | GL752VW                     | [fdbf44e446](https://linux-hardware.org/?probe=fdbf44e446) | May 18, 2025 |
| Google        | Sasuke                      | [e7c2a92c9b](https://linux-hardware.org/?probe=e7c2a92c9b) | May 17, 2025 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3573b94fb8](https://linux-hardware.org/?probe=3573b94fb8) | May 17, 2025 |
| Dell          | Vostro 3500                 | [e045997920](https://linux-hardware.org/?probe=e045997920) | May 16, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [c445378496](https://linux-hardware.org/?probe=c445378496) | May 16, 2025 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [26830b7e18](https://linux-hardware.org/?probe=26830b7e18) | May 16, 2025 |
| HP            | EliteBook 845 G8 Noteboo... | [ea5eb1b9a4](https://linux-hardware.org/?probe=ea5eb1b9a4) | May 16, 2025 |
| Unknown       | TX15                        | [2b679370db](https://linux-hardware.org/?probe=2b679370db) | May 16, 2025 |
| TongFang      | GX5MRXL                     | [637f772afc](https://linux-hardware.org/?probe=637f772afc) | May 15, 2025 |
| HP            | Laptop 15s-du3xxx           | [f7bb1043c0](https://linux-hardware.org/?probe=f7bb1043c0) | May 15, 2025 |
| Acer          | Aspire A515-54              | [57b442620b](https://linux-hardware.org/?probe=57b442620b) | May 14, 2025 |
| HP            | ProBook 450 G6              | [3af2cf2eef](https://linux-hardware.org/?probe=3af2cf2eef) | May 14, 2025 |
| Alienware     | 17 R4                       | [146beb2e13](https://linux-hardware.org/?probe=146beb2e13) | May 14, 2025 |
| HP            | Pavilion Sleekbook 14 PC    | [cc2c1bc710](https://linux-hardware.org/?probe=cc2c1bc710) | May 14, 2025 |
| Dell          | G7 7588                     | [69bb9e2c7e](https://linux-hardware.org/?probe=69bb9e2c7e) | May 13, 2025 |
| HP            | Presario CQ62               | [48eb034b0a](https://linux-hardware.org/?probe=48eb034b0a) | May 13, 2025 |
| Apple         | MacBookPro8,1               | [7104a36bbf](https://linux-hardware.org/?probe=7104a36bbf) | May 13, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [41fdd83009](https://linux-hardware.org/?probe=41fdd83009) | May 12, 2025 |
| HP            | Laptop 15s-eq3xxx           | [33cc23c449](https://linux-hardware.org/?probe=33cc23c449) | May 12, 2025 |
| HP            | EliteBook 840 G1            | [164fd32025](https://linux-hardware.org/?probe=164fd32025) | May 11, 2025 |
| Lenovo        | ThinkPad T495 20NKS29V00    | [f7214549ce](https://linux-hardware.org/?probe=f7214549ce) | May 11, 2025 |
| Fujitsu       | CELSIUS H730                | [1268963e77](https://linux-hardware.org/?probe=1268963e77) | May 11, 2025 |
| Apple         | MacBookPro10,1              | [4272c7f642](https://linux-hardware.org/?probe=4272c7f642) | May 11, 2025 |
| Samsung       | 550XED                      | [84c546a2da](https://linux-hardware.org/?probe=84c546a2da) | May 10, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5ba549b393](https://linux-hardware.org/?probe=5ba549b393) | May 10, 2025 |
| Acer          | Aspire A315-44P             | [70f8a964a9](https://linux-hardware.org/?probe=70f8a964a9) | May 09, 2025 |
| NOBLEX        | SF20BA                      | [124bd008a7](https://linux-hardware.org/?probe=124bd008a7) | May 09, 2025 |
| Dell          | Inspiron N4010              | [5d3d2f7765](https://linux-hardware.org/?probe=5d3d2f7765) | May 09, 2025 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [83e996d508](https://linux-hardware.org/?probe=83e996d508) | May 09, 2025 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [04074f29ca](https://linux-hardware.org/?probe=04074f29ca) | May 09, 2025 |
| System76      | Gazelle                     | [9eadffb40b](https://linux-hardware.org/?probe=9eadffb40b) | May 08, 2025 |
| HP            | OMEN by Laptop 17-ck2xxx    | [02c550b01c](https://linux-hardware.org/?probe=02c550b01c) | May 08, 2025 |
| Chuwi         | GemiBook Plus               | [6f52fea97c](https://linux-hardware.org/?probe=6f52fea97c) | May 07, 2025 |
| Apple         | MacBookPro11,3              | [42f32b8207](https://linux-hardware.org/?probe=42f32b8207) | May 07, 2025 |
| HP            | Dragonfly Pro Laptop PC     | [1775caec36](https://linux-hardware.org/?probe=1775caec36) | May 07, 2025 |
| Dell          | Latitude 7420               | [2a3f507b40](https://linux-hardware.org/?probe=2a3f507b40) | May 07, 2025 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | [54905c81bf](https://linux-hardware.org/?probe=54905c81bf) | May 06, 2025 |
| Lenovo        | IdeaPad S340-14API 81NB     | [09a1adf45d](https://linux-hardware.org/?probe=09a1adf45d) | May 06, 2025 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | [50b98e241f](https://linux-hardware.org/?probe=50b98e241f) | May 06, 2025 |
| Acer          | Predator PH315-54           | [6b9b716c35](https://linux-hardware.org/?probe=6b9b716c35) | May 06, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [ca69c61d60](https://linux-hardware.org/?probe=ca69c61d60) | May 06, 2025 |
| Apple         | MacBookPro10,1              | [ec61acb092](https://linux-hardware.org/?probe=ec61acb092) | May 05, 2025 |
| ASUSTek       | GL553VE                     | [86218432c6](https://linux-hardware.org/?probe=86218432c6) | May 04, 2025 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [7658f7c994](https://linux-hardware.org/?probe=7658f7c994) | May 04, 2025 |
| MSI           | Prestige 16 AI Evo B1MG     | [af711a0e3d](https://linux-hardware.org/?probe=af711a0e3d) | May 04, 2025 |
| HP            | OMEN Gaming Laptop 16-ae... | [fd0dbb9a2e](https://linux-hardware.org/?probe=fd0dbb9a2e) | May 04, 2025 |
| System76      | Darter Pro                  | [d8226488ae](https://linux-hardware.org/?probe=d8226488ae) | May 03, 2025 |
| MSI           | Katana 15 B13VFK            | [d002135e86](https://linux-hardware.org/?probe=d002135e86) | May 03, 2025 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [75f0541d37](https://linux-hardware.org/?probe=75f0541d37) | May 03, 2025 |
| Intel         | AH16                        | [4da20f52a8](https://linux-hardware.org/?probe=4da20f52a8) | May 03, 2025 |
| Acer          | Aspire V3-571G              | [766b12a5d1](https://linux-hardware.org/?probe=766b12a5d1) | May 03, 2025 |
| Intel Clie... | LAPQC71A                    | [14beba1eff](https://linux-hardware.org/?probe=14beba1eff) | May 03, 2025 |
| Apple         | MacBookAir7,2               | [88f0b0f9c0](https://linux-hardware.org/?probe=88f0b0f9c0) | May 03, 2025 |
| Dell          | Latitude E7270              | [06ec8bfa60](https://linux-hardware.org/?probe=06ec8bfa60) | May 02, 2025 |
| Apple         | MacBookPro9,2               | [af7f6e2712](https://linux-hardware.org/?probe=af7f6e2712) | May 02, 2025 |
| Apple         | MacBookPro11,3              | [3d8eaae696](https://linux-hardware.org/?probe=3d8eaae696) | May 02, 2025 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [acdb86d0e7](https://linux-hardware.org/?probe=acdb86d0e7) | May 02, 2025 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [ab24c594d2](https://linux-hardware.org/?probe=ab24c594d2) | May 02, 2025 |
| Acer          | Aspire V3-572G              | [8719a8dad9](https://linux-hardware.org/?probe=8719a8dad9) | May 01, 2025 |
| Alienware     | M17xR4                      | [91a3740544](https://linux-hardware.org/?probe=91a3740544) | May 01, 2025 |
| HP            | Laptop 15s-eq2xxx           | [de211d4542](https://linux-hardware.org/?probe=de211d4542) | Apr 29, 2025 |
| NEC Comput... | PC-VKT12HZG1                | [0dfa9dccbc](https://linux-hardware.org/?probe=0dfa9dccbc) | Apr 29, 2025 |
| HP            | Victus by Gaming Laptop ... | [091321557a](https://linux-hardware.org/?probe=091321557a) | Apr 29, 2025 |
| HP            | Victus by Gaming Laptop ... | [ab57ff11b4](https://linux-hardware.org/?probe=ab57ff11b4) | Apr 29, 2025 |
| System76      | Darter Pro                  | [9d1a488e72](https://linux-hardware.org/?probe=9d1a488e72) | Apr 29, 2025 |
| Lenovo        | ThinkBook 14-IML 20RV       | [114cdb62d1](https://linux-hardware.org/?probe=114cdb62d1) | Apr 28, 2025 |
| Acer          | Aspire A515-54              | [e416137d59](https://linux-hardware.org/?probe=e416137d59) | Apr 28, 2025 |
| HP            | Victus by Laptop 16-e0xx... | [e724e79019](https://linux-hardware.org/?probe=e724e79019) | Apr 28, 2025 |
| MSI           | Z170A GAMING M7             | [01cdf4c2fe](https://linux-hardware.org/?probe=01cdf4c2fe) | Apr 28, 2025 |
| Dell          | XPS 15 7590                 | [bbe0132fdd](https://linux-hardware.org/?probe=bbe0132fdd) | Apr 28, 2025 |
| ASUSTek       | ProArt P16 H7606WV_H7606... | [c924dd7e91](https://linux-hardware.org/?probe=c924dd7e91) | Apr 28, 2025 |
| System76      | Oryx Pro                    | [794104e829](https://linux-hardware.org/?probe=794104e829) | Apr 28, 2025 |
| ARDOR GAMI... | V15x_V17xRNx                | [5f850a6551](https://linux-hardware.org/?probe=5f850a6551) | Apr 28, 2025 |
| Acer          | Aspire V3-572G              | [8eb3c5644e](https://linux-hardware.org/?probe=8eb3c5644e) | Apr 27, 2025 |
| Schenker      | XMG CORE (REN/E21)          | [1bcc3823ed](https://linux-hardware.org/?probe=1bcc3823ed) | Apr 27, 2025 |
| Schenker      | XMG CORE (REN/E21)          | [16292506cf](https://linux-hardware.org/?probe=16292506cf) | Apr 27, 2025 |
| Dell          | Inspiron 15 7510            | [58f2cd330f](https://linux-hardware.org/?probe=58f2cd330f) | Apr 27, 2025 |
| Dell          | Inspiron 5770               | [1a1f8fc7ba](https://linux-hardware.org/?probe=1a1f8fc7ba) | Apr 27, 2025 |
| Dell          | Latitude E6500              | [9e60170d7f](https://linux-hardware.org/?probe=9e60170d7f) | Apr 27, 2025 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [a79fb6446c](https://linux-hardware.org/?probe=a79fb6446c) | Apr 27, 2025 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | [105d49b21f](https://linux-hardware.org/?probe=105d49b21f) | Apr 26, 2025 |
| MSI           | GS66 Stealth 10UG           | [dab6be5281](https://linux-hardware.org/?probe=dab6be5281) | Apr 24, 2025 |
| Dell          | Inspiron 14 5445            | [6ca086eb0c](https://linux-hardware.org/?probe=6ca086eb0c) | Apr 23, 2025 |
| MSI           | Z170A GAMING M7             | [500ab26758](https://linux-hardware.org/?probe=500ab26758) | Apr 23, 2025 |
| Shenzhen R... | X16 Extreme Pro             | [56c46a3623](https://linux-hardware.org/?probe=56c46a3623) | Apr 23, 2025 |
| Acer          | Aspire A515-54              | [b7b72d7af8](https://linux-hardware.org/?probe=b7b72d7af8) | Apr 23, 2025 |
| System76      | Pangolin                    | [040351aa05](https://linux-hardware.org/?probe=040351aa05) | Apr 23, 2025 |
| System76      | Pangolin                    | [2170b823e3](https://linux-hardware.org/?probe=2170b823e3) | Apr 23, 2025 |
| Infinix       | INBOOK Y1 PLUS              | [0889d99164](https://linux-hardware.org/?probe=0889d99164) | Apr 22, 2025 |
| System76      | Darter Pro                  | [a338fb16fe](https://linux-hardware.org/?probe=a338fb16fe) | Apr 22, 2025 |
| Gateway       | NV57H                       | [24cfc925eb](https://linux-hardware.org/?probe=24cfc925eb) | Apr 21, 2025 |
| LG Electro... | 14Z90Q-G.AA76B              | [1555e054cc](https://linux-hardware.org/?probe=1555e054cc) | Apr 21, 2025 |
| HP            | ProBook 4421s               | [02e93a1c9a](https://linux-hardware.org/?probe=02e93a1c9a) | Apr 21, 2025 |
| HP            | ProBook 4421s               | [844511443f](https://linux-hardware.org/?probe=844511443f) | Apr 21, 2025 |
| Apple         | MacBookPro12,1              | [d54c4eb1fe](https://linux-hardware.org/?probe=d54c4eb1fe) | Apr 21, 2025 |
| HP            | Victus by Gaming Laptop ... | [d65b5ba036](https://linux-hardware.org/?probe=d65b5ba036) | Apr 20, 2025 |
| Lenovo        | Unknown                     | [6f26bbcef8](https://linux-hardware.org/?probe=6f26bbcef8) | Apr 20, 2025 |
| Lenovo        | Legion Slim 5 16AHP9 83D... | [bf56369ddd](https://linux-hardware.org/?probe=bf56369ddd) | Apr 20, 2025 |
| ASUSTek       | G74Sx                       | [5645f7e84d](https://linux-hardware.org/?probe=5645f7e84d) | Apr 20, 2025 |
| Apple         | MacBookPro11,3              | [cd1e1da3c5](https://linux-hardware.org/?probe=cd1e1da3c5) | Apr 20, 2025 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [028c30096f](https://linux-hardware.org/?probe=028c30096f) | Apr 19, 2025 |
| Dell          | Inspiron 3543               | [bee4ef5664](https://linux-hardware.org/?probe=bee4ef5664) | Apr 19, 2025 |
| Shenzhen R... | X16 Extreme Pro             | [d4ac82f56c](https://linux-hardware.org/?probe=d4ac82f56c) | Apr 18, 2025 |
| MSI           | GF63 8RD                    | [254b5f9de9](https://linux-hardware.org/?probe=254b5f9de9) | Apr 18, 2025 |
| Sony          | VJPG11                      | [f13f61e34f](https://linux-hardware.org/?probe=f13f61e34f) | Apr 18, 2025 |
| Lenovo        | ThinkPad P50 20EQS2NM00     | [1a9202c5c2](https://linux-hardware.org/?probe=1a9202c5c2) | Apr 17, 2025 |
| System76      | Adder WS                    | [3288b9b9a9](https://linux-hardware.org/?probe=3288b9b9a9) | Apr 17, 2025 |
| Dell          | Latitude 7390               | [f79b0ffd90](https://linux-hardware.org/?probe=f79b0ffd90) | Apr 16, 2025 |
| Dell          | XPS 9320                    | [4dd9a09f7e](https://linux-hardware.org/?probe=4dd9a09f7e) | Apr 16, 2025 |
| ASUSTek       | X550LN                      | [f55b9dd373](https://linux-hardware.org/?probe=f55b9dd373) | Apr 15, 2025 |
| Lenovo        | ThinkPad X260 20F5S5E200    | [83ad9aaca5](https://linux-hardware.org/?probe=83ad9aaca5) | Apr 15, 2025 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [9a7653c977](https://linux-hardware.org/?probe=9a7653c977) | Apr 15, 2025 |
| HP            | ZBook 17 G3                 | [42287104d0](https://linux-hardware.org/?probe=42287104d0) | Apr 14, 2025 |
| Dell          | Inspiron 16 Plus 7640       | [27d0619a10](https://linux-hardware.org/?probe=27d0619a10) | Apr 14, 2025 |
| Lenovo        | ThinkPad E14 20RB000QBR     | [0ccc08d58b](https://linux-hardware.org/?probe=0ccc08d58b) | Apr 14, 2025 |
| Lenovo        | ThinkPad E14 20RB000QBR     | [131ce614e4](https://linux-hardware.org/?probe=131ce614e4) | Apr 14, 2025 |
| ASUSTek       | ROG Strix G18 G834JZR_G8... | [2e16f610de](https://linux-hardware.org/?probe=2e16f610de) | Apr 14, 2025 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | [fa9484c3d7](https://linux-hardware.org/?probe=fa9484c3d7) | Apr 13, 2025 |
| Apple         | MacBookPro11,1              | [42cffd237a](https://linux-hardware.org/?probe=42cffd237a) | Apr 13, 2025 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [92a86334fc](https://linux-hardware.org/?probe=92a86334fc) | Apr 13, 2025 |
| HP            | EliteBook 840 G1            | [194ddbd68d](https://linux-hardware.org/?probe=194ddbd68d) | Apr 13, 2025 |
| Lenovo        | Legion 5 15ARH7 82RE        | [2f120b8144](https://linux-hardware.org/?probe=2f120b8144) | Apr 13, 2025 |
| HP            | Pavilion Laptop 15-eg0xx... | [10589efd75](https://linux-hardware.org/?probe=10589efd75) | Apr 13, 2025 |
| ASUSTek       | X555LF                      | [c3697a155f](https://linux-hardware.org/?probe=c3697a155f) | Apr 12, 2025 |
| Dell          | Precision 5520              | [4ab28be1ee](https://linux-hardware.org/?probe=4ab28be1ee) | Apr 12, 2025 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [a0e3778bdd](https://linux-hardware.org/?probe=a0e3778bdd) | Apr 12, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [2149720f63](https://linux-hardware.org/?probe=2149720f63) | Apr 11, 2025 |
| Apple         | MacBookPro5,5               | [35f98c7109](https://linux-hardware.org/?probe=35f98c7109) | Apr 10, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [ac6a4c13e2](https://linux-hardware.org/?probe=ac6a4c13e2) | Apr 10, 2025 |
| HP            | EliteBook 840 G3            | [d2cceb8259](https://linux-hardware.org/?probe=d2cceb8259) | Apr 10, 2025 |
| Toshiba       | PORTEGE Z30t-A              | [871b0d2df6](https://linux-hardware.org/?probe=871b0d2df6) | Apr 09, 2025 |
| Positivo B... | VJFE69F11X-B0911H           | [72ffec2faf](https://linux-hardware.org/?probe=72ffec2faf) | Apr 09, 2025 |
| Positivo B... | VJFE69F11X-B0911H           | [8e103cfa11](https://linux-hardware.org/?probe=8e103cfa11) | Apr 09, 2025 |
| Lenovo        | Edge 15 80K9                | [32e475ba29](https://linux-hardware.org/?probe=32e475ba29) | Apr 09, 2025 |
| Apple         | MacBookAir7,2               | [566398781b](https://linux-hardware.org/?probe=566398781b) | Apr 09, 2025 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [79c439b581](https://linux-hardware.org/?probe=79c439b581) | Apr 08, 2025 |
| Dell          | Inspiron 7472               | [2771c8e3e7](https://linux-hardware.org/?probe=2771c8e3e7) | Apr 08, 2025 |
| Dell          | Inspiron 7472               | [8260209987](https://linux-hardware.org/?probe=8260209987) | Apr 08, 2025 |
| Samsung       | 750XGK                      | [48f4d0ab2b](https://linux-hardware.org/?probe=48f4d0ab2b) | Apr 08, 2025 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [740f3c906a](https://linux-hardware.org/?probe=740f3c906a) | Apr 08, 2025 |
| Lenovo        | ThinkPad E14 Gen 5 21JRS... | [0bede03424](https://linux-hardware.org/?probe=0bede03424) | Apr 08, 2025 |
| MSI           | GE62 6QF                    | [707974ca83](https://linux-hardware.org/?probe=707974ca83) | Apr 07, 2025 |
| Unknown       | Unknown                     | [8caf0a0ee5](https://linux-hardware.org/?probe=8caf0a0ee5) | Apr 07, 2025 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | [b2b5ce9739](https://linux-hardware.org/?probe=b2b5ce9739) | Apr 05, 2025 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [de503b52c0](https://linux-hardware.org/?probe=de503b52c0) | Apr 05, 2025 |
| Acer          | Swift SFX14-41G             | [0388cacd7c](https://linux-hardware.org/?probe=0388cacd7c) | Apr 04, 2025 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [da6aed3b55](https://linux-hardware.org/?probe=da6aed3b55) | Apr 04, 2025 |
| Lenovo        | ThinkPad T470 20HES3JR03    | [b4d2b5a832](https://linux-hardware.org/?probe=b4d2b5a832) | Apr 03, 2025 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [19596cd5ab](https://linux-hardware.org/?probe=19596cd5ab) | Apr 03, 2025 |
| System76      | Adder WS                    | [3de4df5eda](https://linux-hardware.org/?probe=3de4df5eda) | Apr 03, 2025 |
| Dell          | Latitude E5520              | [c6d39b8fec](https://linux-hardware.org/?probe=c6d39b8fec) | Apr 03, 2025 |
| Lenovo        | IdeaPad Slim 5 16AHP9 83... | [051f89d8ed](https://linux-hardware.org/?probe=051f89d8ed) | Apr 02, 2025 |
| Panasonic     | FZ55-1                      | [6b67c3d8f9](https://linux-hardware.org/?probe=6b67c3d8f9) | Apr 02, 2025 |
| Panasonic     | FZ55-1                      | [14cee48878](https://linux-hardware.org/?probe=14cee48878) | Apr 02, 2025 |
| HP            | Dragonfly Pro Laptop PC     | [97ee920659](https://linux-hardware.org/?probe=97ee920659) | Apr 02, 2025 |
| Lenovo        | ThinkPad T14s Gen 6 21M1... | [fbda73a703](https://linux-hardware.org/?probe=fbda73a703) | Apr 01, 2025 |
| Sony          | VPCZ120GL                   | [ad6c8045fe](https://linux-hardware.org/?probe=ad6c8045fe) | Apr 01, 2025 |
| Dell          | Vostro 3560                 | [2cb789a649](https://linux-hardware.org/?probe=2cb789a649) | Apr 01, 2025 |
| Lenovo        | IdeaPad Slim 5 16AHP9 83... | [f3b9521850](https://linux-hardware.org/?probe=f3b9521850) | Mar 31, 2025 |
| HP            | Pavilion Laptop 15-eg0xx... | [e78e91fd2b](https://linux-hardware.org/?probe=e78e91fd2b) | Mar 30, 2025 |
| Dell          | Precision 5520              | [920aa7a6b7](https://linux-hardware.org/?probe=920aa7a6b7) | Mar 30, 2025 |
| Valve         | Jupiter                     | [ad7a694891](https://linux-hardware.org/?probe=ad7a694891) | Mar 30, 2025 |
| Samsung       | 300E5K/300E5Q               | [d91b3d833e](https://linux-hardware.org/?probe=d91b3d833e) | Mar 30, 2025 |
| Dell          | Vostro 3560                 | [ea79fd7839](https://linux-hardware.org/?probe=ea79fd7839) | Mar 30, 2025 |
| Acer          | Nitro ANV15-51              | [5f46f5b244](https://linux-hardware.org/?probe=5f46f5b244) | Mar 29, 2025 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [9d5d3df639](https://linux-hardware.org/?probe=9d5d3df639) | Mar 29, 2025 |
| MSI           | PS63 Modern 8RC             | [7ab5de1f69](https://linux-hardware.org/?probe=7ab5de1f69) | Mar 29, 2025 |
| Acer          | Nitro ANV15-51              | [97be52c0e4](https://linux-hardware.org/?probe=97be52c0e4) | Mar 29, 2025 |
| HP            | Laptop 17-ak0xx             | [83dddca38a](https://linux-hardware.org/?probe=83dddca38a) | Mar 28, 2025 |
| Apple         | MacBookAir7,2               | [4d60e68844](https://linux-hardware.org/?probe=4d60e68844) | Mar 27, 2025 |
| Apple         | MacBook4,1                  | [cb70062941](https://linux-hardware.org/?probe=cb70062941) | Mar 27, 2025 |
| Lenovo        | ThinkPad T420 4180AG8       | [73cf848abe](https://linux-hardware.org/?probe=73cf848abe) | Mar 27, 2025 |
| Dell          | Latitude E7450              | [88f4547d89](https://linux-hardware.org/?probe=88f4547d89) | Mar 26, 2025 |
| Toshiba       | dynabook T45/RGY            | [2b59e2eac5](https://linux-hardware.org/?probe=2b59e2eac5) | Mar 26, 2025 |
| HP            | 245 14 inch G9              | [9f79bf7878](https://linux-hardware.org/?probe=9f79bf7878) | Mar 25, 2025 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [303674470a](https://linux-hardware.org/?probe=303674470a) | Mar 25, 2025 |
| HP            | Pavilion dv7                | [e376062c9a](https://linux-hardware.org/?probe=e376062c9a) | Mar 24, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [552871c459](https://linux-hardware.org/?probe=552871c459) | Mar 24, 2025 |
| HP            | OMEN Laptop 15-en1xxx       | [5fc18278a6](https://linux-hardware.org/?probe=5fc18278a6) | Mar 24, 2025 |
| HP            | Pavilion Notebook           | [cb59ba8165](https://linux-hardware.org/?probe=cb59ba8165) | Mar 24, 2025 |
| HP            | Pavilion Notebook           | [148a068588](https://linux-hardware.org/?probe=148a068588) | Mar 24, 2025 |
| Dell          | Inspiron 3583               | [eda5dc40fa](https://linux-hardware.org/?probe=eda5dc40fa) | Mar 23, 2025 |
| ASUSTek       | X550JK                      | [1ae4ee9207](https://linux-hardware.org/?probe=1ae4ee9207) | Mar 23, 2025 |
| System76      | Darter Pro                  | [49629b1f3a](https://linux-hardware.org/?probe=49629b1f3a) | Mar 23, 2025 |
| HP            | Pavilion Laptop 15-eg0xx... | [01aa71df0c](https://linux-hardware.org/?probe=01aa71df0c) | Mar 23, 2025 |
| System76      | Darter Pro                  | [1a37c02712](https://linux-hardware.org/?probe=1a37c02712) | Mar 23, 2025 |
| HP            | 355 G2                      | [da41c8fa00](https://linux-hardware.org/?probe=da41c8fa00) | Mar 23, 2025 |
| HP            | 355 G2                      | [8ccd514031](https://linux-hardware.org/?probe=8ccd514031) | Mar 23, 2025 |
| Apple         | MacBookPro12,1              | [20258d9bee](https://linux-hardware.org/?probe=20258d9bee) | Mar 23, 2025 |
| Apple         | MacBookPro12,1              | [6df69ef3a4](https://linux-hardware.org/?probe=6df69ef3a4) | Mar 22, 2025 |
| HP            | Pavilion dv6                | [fbd6b31972](https://linux-hardware.org/?probe=fbd6b31972) | Mar 22, 2025 |
| Lenovo        | ThinkPad E16 Gen 2 21M50... | [259176c0c6](https://linux-hardware.org/?probe=259176c0c6) | Mar 21, 2025 |
| HP            | Pavilion Aero Laptop 13-... | [e38ebae82c](https://linux-hardware.org/?probe=e38ebae82c) | Mar 21, 2025 |
| Dell          | Latitude 7300               | [2f17e5e794](https://linux-hardware.org/?probe=2f17e5e794) | Mar 21, 2025 |
| Dell          | XPS 15 9570                 | [971cc31bad](https://linux-hardware.org/?probe=971cc31bad) | Mar 21, 2025 |
| System76      | Oryx Pro                    | [1d5e785e0c](https://linux-hardware.org/?probe=1d5e785e0c) | Mar 21, 2025 |
| Acer          | Nitro ANV15-51              | [adbc38cd32](https://linux-hardware.org/?probe=adbc38cd32) | Mar 21, 2025 |
| HP            | ProBook 4710s               | [fe15c024da](https://linux-hardware.org/?probe=fe15c024da) | Mar 21, 2025 |
| Lenovo        | ThinkPad P50 20EQS1P700     | [d100366c59](https://linux-hardware.org/?probe=d100366c59) | Mar 21, 2025 |
| Samsung       | 550XED                      | [726f383a3e](https://linux-hardware.org/?probe=726f383a3e) | Mar 21, 2025 |
| HP            | 250 G4                      | [66e008c250](https://linux-hardware.org/?probe=66e008c250) | Mar 21, 2025 |
| Lenovo        | Z51-70 80K6                 | [555347babc](https://linux-hardware.org/?probe=555347babc) | Mar 20, 2025 |
| HP            | Dragonfly Pro Laptop PC     | [8ae5e4df92](https://linux-hardware.org/?probe=8ae5e4df92) | Mar 20, 2025 |
| ASUSTek       | ROG Strix SCAR 18 G834JY... | [193813b3f7](https://linux-hardware.org/?probe=193813b3f7) | Mar 20, 2025 |
| Lenovo        | VILG1                       | [256116bd90](https://linux-hardware.org/?probe=256116bd90) | Mar 20, 2025 |
| Lenovo        | ThinkPad E15 Gen 4 21E70... | [56a0d18435](https://linux-hardware.org/?probe=56a0d18435) | Mar 20, 2025 |
| HP            | Pavilion Laptop 15-eg0xx... | [2bf173ea65](https://linux-hardware.org/?probe=2bf173ea65) | Mar 19, 2025 |
| Lenovo        | ThinkPad E15 Gen 4 21E70... | [a7d561f789](https://linux-hardware.org/?probe=a7d561f789) | Mar 19, 2025 |
| Notebook      | W35xSTQ_370ST               | [f71c6de37b](https://linux-hardware.org/?probe=f71c6de37b) | Mar 18, 2025 |
| Dell          | XPS 15 9530                 | [2d61d7d0d1](https://linux-hardware.org/?probe=2d61d7d0d1) | Mar 18, 2025 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [d217ef1293](https://linux-hardware.org/?probe=d217ef1293) | Mar 18, 2025 |
| Dell          | Latitude 5501               | [eb7ee63034](https://linux-hardware.org/?probe=eb7ee63034) | Mar 18, 2025 |
| MSI           | GT72VR 6RD                  | [51b85c1ece](https://linux-hardware.org/?probe=51b85c1ece) | Mar 18, 2025 |
| Dell          | Latitude 5501               | [54e6c5de8a](https://linux-hardware.org/?probe=54e6c5de8a) | Mar 17, 2025 |
| Dell          | G15 5530                    | [403556a3ed](https://linux-hardware.org/?probe=403556a3ed) | Mar 17, 2025 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [26327f0a61](https://linux-hardware.org/?probe=26327f0a61) | Mar 17, 2025 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [52713bbcec](https://linux-hardware.org/?probe=52713bbcec) | Mar 17, 2025 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [d1b7a94569](https://linux-hardware.org/?probe=d1b7a94569) | Mar 17, 2025 |
| ASUSTek       | G75VX                       | [52202acb9e](https://linux-hardware.org/?probe=52202acb9e) | Mar 17, 2025 |
| Dell          | Precision 5690              | [e2fa07e9a2](https://linux-hardware.org/?probe=e2fa07e9a2) | Mar 17, 2025 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [5d9bda93a0](https://linux-hardware.org/?probe=5d9bda93a0) | Mar 16, 2025 |
| HUAWEI        | BOD-WXX9                    | [de9f2b126d](https://linux-hardware.org/?probe=de9f2b126d) | Mar 16, 2025 |
| ASUSTek       | ROG Strix SCAR 18 G834JY... | [457f7776f2](https://linux-hardware.org/?probe=457f7776f2) | Mar 16, 2025 |
| Apple         | MacBookPro9,2               | [81d53cdc8d](https://linux-hardware.org/?probe=81d53cdc8d) | Mar 15, 2025 |
| Apple         | MacBookPro9,2               | [fb1d745d02](https://linux-hardware.org/?probe=fb1d745d02) | Mar 15, 2025 |
| Alienware     | m16 R1                      | [afeac5e82c](https://linux-hardware.org/?probe=afeac5e82c) | Mar 15, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [1777f690a1](https://linux-hardware.org/?probe=1777f690a1) | Mar 15, 2025 |
| Lenovo        | G500 20236                  | [b47f403d4d](https://linux-hardware.org/?probe=b47f403d4d) | Mar 15, 2025 |
| ASUSTek       | ZenBook 13 UX310UFR         | [bf8c33329f](https://linux-hardware.org/?probe=bf8c33329f) | Mar 14, 2025 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [7be920486a](https://linux-hardware.org/?probe=7be920486a) | Mar 14, 2025 |
| ASUSTek       | ROG Strix SCAR 18 G834JY... | [9dd59508d9](https://linux-hardware.org/?probe=9dd59508d9) | Mar 14, 2025 |
| ASUSTek       | ZenBook 13 UX310UFR         | [e647d35051](https://linux-hardware.org/?probe=e647d35051) | Mar 13, 2025 |
| HP            | Pavilion HDX9300            | [f3e9e45bba](https://linux-hardware.org/?probe=f3e9e45bba) | Mar 13, 2025 |
| Acer          | Aspire A515-45              | [65b981a359](https://linux-hardware.org/?probe=65b981a359) | Mar 13, 2025 |
| Dell          | Latitude E6520              | [2456e2a2a5](https://linux-hardware.org/?probe=2456e2a2a5) | Mar 13, 2025 |
| Toshiba       | Satellite L55-B             | [f498575a9c](https://linux-hardware.org/?probe=f498575a9c) | Mar 13, 2025 |
| Dell          | Latitude E5570              | [a54b018322](https://linux-hardware.org/?probe=a54b018322) | Mar 12, 2025 |
| Apple         | MacBookPro15,1              | [fc076d436a](https://linux-hardware.org/?probe=fc076d436a) | Mar 12, 2025 |
| Unknown       | Unknown                     | [bd21d6a083](https://linux-hardware.org/?probe=bd21d6a083) | Mar 12, 2025 |
| Sony          | VGN-FW51MF_H                | [039b1f998d](https://linux-hardware.org/?probe=039b1f998d) | Mar 12, 2025 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [00c288a316](https://linux-hardware.org/?probe=00c288a316) | Mar 12, 2025 |
| Apple         | MacBookPro8,2               | [b8af6ea947](https://linux-hardware.org/?probe=b8af6ea947) | Mar 11, 2025 |
| Chuwi         | GemiBook Plus               | [98b7fe1b29](https://linux-hardware.org/?probe=98b7fe1b29) | Mar 11, 2025 |
| Medion        | S6445 MD61489               | [969c6ab3b1](https://linux-hardware.org/?probe=969c6ab3b1) | Mar 10, 2025 |
| Dell          | Inspiron 5447               | [e2ccaf02f4](https://linux-hardware.org/?probe=e2ccaf02f4) | Mar 10, 2025 |
| Dell          | Inspiron 7348               | [0c65db6f8b](https://linux-hardware.org/?probe=0c65db6f8b) | Mar 09, 2025 |
| ASUSTek       | G750JZA                     | [875a2ac76a](https://linux-hardware.org/?probe=875a2ac76a) | Mar 09, 2025 |
| MSI           | Pulse 15 B13VFK             | [768935118d](https://linux-hardware.org/?probe=768935118d) | Mar 08, 2025 |
| Samsung       | 530E5M                      | [87e16a95bd](https://linux-hardware.org/?probe=87e16a95bd) | Mar 08, 2025 |
| HP            | Pavilion Laptop 14-ce0xx... | [5663c266ae](https://linux-hardware.org/?probe=5663c266ae) | Mar 08, 2025 |
| Samsung       | 530E5M                      | [c0cec86249](https://linux-hardware.org/?probe=c0cec86249) | Mar 08, 2025 |
| Google        | Atlas                       | [f9ad33f301](https://linux-hardware.org/?probe=f9ad33f301) | Mar 08, 2025 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [724bc350df](https://linux-hardware.org/?probe=724bc350df) | Mar 08, 2025 |
| Apple         | MacBookAir7,2               | [89e6433a41](https://linux-hardware.org/?probe=89e6433a41) | Mar 08, 2025 |
| Dell          | System Inspiron N7110       | [846a9c8837](https://linux-hardware.org/?probe=846a9c8837) | Mar 07, 2025 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [93b4a52ba4](https://linux-hardware.org/?probe=93b4a52ba4) | Mar 07, 2025 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [e8fdf94778](https://linux-hardware.org/?probe=e8fdf94778) | Mar 07, 2025 |
| Apple         | MacBook8,1                  | [c554c516ae](https://linux-hardware.org/?probe=c554c516ae) | Mar 07, 2025 |
| HP            | 250 G4                      | [b18ea1c075](https://linux-hardware.org/?probe=b18ea1c075) | Mar 06, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [d6c87abe56](https://linux-hardware.org/?probe=d6c87abe56) | Mar 06, 2025 |
| Dell          | Precision 5530              | [7124fa7ad5](https://linux-hardware.org/?probe=7124fa7ad5) | Mar 06, 2025 |
| Lenovo        | ThinkPad T490 20N2S04T00    | [76918274cc](https://linux-hardware.org/?probe=76918274cc) | Mar 05, 2025 |
| Positivo      | CI7161128GBW10              | [6a825adb98](https://linux-hardware.org/?probe=6a825adb98) | Mar 04, 2025 |
| HP            | ProBook 450 G6              | [62f383291a](https://linux-hardware.org/?probe=62f383291a) | Mar 04, 2025 |
| HP            | ProBook 450 G6              | [7f355579dd](https://linux-hardware.org/?probe=7f355579dd) | Mar 04, 2025 |
| Lenovo        | Y520-15IKBN 80WK            | [9faeebc956](https://linux-hardware.org/?probe=9faeebc956) | Mar 04, 2025 |
| Lenovo        | Y520-15IKBN 80WK            | [ea21f45e4f](https://linux-hardware.org/?probe=ea21f45e4f) | Mar 04, 2025 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [40af3b159b](https://linux-hardware.org/?probe=40af3b159b) | Mar 04, 2025 |
| HP            | Dragonfly Pro Laptop PC     | [51c4f29445](https://linux-hardware.org/?probe=51c4f29445) | Mar 04, 2025 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Pop!_OS 22.04 | 3898      | 50.19%  |
| Pop!_OS 20.04 | 1157      | 14.9%   |
| Pop!_OS 21.04 | 965       | 12.43%  |
| Pop!_OS 20.10 | 857       | 11.04%  |
| Pop!_OS 21.10 | 600       | 7.73%   |
| Pop!_OS 24.04 | 242       | 3.12%   |
| Pop!_OS 19.10 | 30        | 0.39%   |
| Pop!_OS 18.04 | 7         | 0.09%   |
| Pop!_OS 19.04 | 6         | 0.08%   |
| Pop!_OS 18.10 | 4         | 0.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Pop!_OS | 7461      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 6.9.3-76060903-generic              | 784       | 9.3%    |
| 6.2.6-76060206-generic              | 480       | 5.7%    |
| 6.12.10-76061203-generic            | 446       | 5.29%   |
| 5.11.0-7620-generic                 | 443       | 5.26%   |
| 5.8.0-7630-generic                  | 380       | 4.51%   |
| 5.4.0-7634-generic                  | 347       | 4.12%   |
| 5.19.0-76051900-generic             | 276       | 3.28%   |
| 6.0.12-76060006-generic             | 273       | 3.24%   |
| 5.13.0-7614-generic                 | 263       | 3.12%   |
| 6.8.0-76060800daily20240311-generic | 261       | 3.1%    |
| 5.4.0-7642-generic                  | 257       | 3.05%   |
| 5.17.5-76051705-generic             | 257       | 3.05%   |
| 5.8.0-7642-generic                  | 243       | 2.88%   |
| 5.11.0-7614-generic                 | 229       | 2.72%   |
| 5.13.0-7620-generic                 | 216       | 2.56%   |
| 6.6.10-76060610-generic             | 191       | 2.27%   |
| 6.4.6-76060406-generic              | 188       | 2.23%   |
| 6.0.6-76060006-generic              | 166       | 1.97%   |
| 6.5.6-76060506-generic              | 163       | 1.93%   |
| 5.15.15-76051515-generic            | 155       | 1.84%   |
| 6.16.3-76061603-generic             | 146       | 1.73%   |
| 5.16.11-76051611-generic            | 139       | 1.65%   |
| 6.6.6-76060606-generic              | 128       | 1.52%   |
| 5.11.0-7612-generic                 | 127       | 1.51%   |
| 5.15.5-76051505-generic             | 124       | 1.47%   |
| 5.18.10-76051810-generic            | 123       | 1.46%   |
| 5.17.15-76051715-generic            | 106       | 1.26%   |
| 5.8.0-7625-generic                  | 105       | 1.25%   |
| 5.11.0-7633-generic                 | 99        | 1.17%   |
| 5.16.19-76051619-generic            | 97        | 1.15%   |
| 5.15.8-76051508-generic             | 97        | 1.15%   |
| 5.16.15-76051615-generic            | 92        | 1.09%   |
| 5.4.0-7626-generic                  | 84        | 1%      |
| 6.2.0-76060200-generic              | 79        | 0.94%   |
| 6.17.9-76061709-generic             | 79        | 0.94%   |
| 6.5.4-76060504-generic              | 66        | 0.78%   |
| 6.17.4-76061704-generic             | 63        | 0.75%   |
| 5.15.11-76051511-generic            | 63        | 0.75%   |
| 6.0.2-76060002-generic              | 59        | 0.7%    |
| 5.15.23-76051523-generic            | 56        | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 875       | 10.52%  |
| 6.9.3   | 784       | 9.42%   |
| 5.4.0   | 746       | 8.97%   |
| 5.8.0   | 698       | 8.39%   |
| 6.2.6   | 481       | 5.78%   |
| 5.13.0  | 466       | 5.6%    |
| 6.12.10 | 447       | 5.37%   |
| 6.0.12  | 281       | 3.38%   |
| 5.19.0  | 279       | 3.35%   |
| 6.8.0   | 262       | 3.15%   |
| 5.17.5  | 260       | 3.12%   |
| 6.6.10  | 191       | 2.3%    |
| 6.4.6   | 188       | 2.26%   |
| 6.0.6   | 166       | 1.99%   |
| 6.5.6   | 163       | 1.96%   |
| 5.15.15 | 155       | 1.86%   |
| 6.16.3  | 146       | 1.75%   |
| 5.16.11 | 139       | 1.67%   |
| 6.6.6   | 128       | 1.54%   |
| 5.15.5  | 124       | 1.49%   |
| 5.18.10 | 123       | 1.48%   |
| 5.17.15 | 106       | 1.27%   |
| 5.16.19 | 97        | 1.17%   |
| 5.15.8  | 97        | 1.17%   |
| 5.16.15 | 92        | 1.11%   |
| 6.2.0   | 79        | 0.95%   |
| 6.17.9  | 79        | 0.95%   |
| 6.5.4   | 66        | 0.79%   |
| 6.17.4  | 63        | 0.76%   |
| 5.15.11 | 63        | 0.76%   |
| 6.0.2   | 60        | 0.72%   |
| 5.15.23 | 56        | 0.67%   |
| 6.1.11  | 54        | 0.65%   |
| 5.3.0   | 32        | 0.38%   |
| 6.0.3   | 24        | 0.29%   |
| 5.19.16 | 21        | 0.25%   |
| 5.0.0   | 6         | 0.07%   |
| 4.18.0  | 6         | 0.07%   |
| 5.15.0  | 5         | 0.06%   |
| 5.7.0   | 4         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 882       | 10.69%  |
| 6.9     | 785       | 9.51%   |
| 5.4     | 747       | 9.05%   |
| 5.8     | 712       | 8.63%   |
| 6.2     | 560       | 6.79%   |
| 6.0     | 516       | 6.25%   |
| 5.15    | 496       | 6.01%   |
| 5.13    | 478       | 5.79%   |
| 6.12    | 455       | 5.51%   |
| 5.17    | 366       | 4.44%   |
| 5.16    | 327       | 3.96%   |
| 6.6     | 312       | 3.78%   |
| 5.19    | 302       | 3.66%   |
| 6.8     | 263       | 3.19%   |
| 6.5     | 236       | 2.86%   |
| 6.4     | 192       | 2.33%   |
| 6.16    | 147       | 1.78%   |
| 6.17    | 143       | 1.73%   |
| 5.18    | 127       | 1.54%   |
| 6.1     | 61        | 0.74%   |
| 5.3     | 32        | 0.39%   |
| 5.10    | 18        | 0.22%   |
| 5.12    | 14        | 0.17%   |
| 5.7     | 11        | 0.13%   |
| 5.14    | 11        | 0.13%   |
| 5.9     | 9         | 0.11%   |
| 6.3     | 8         | 0.1%    |
| 5.6     | 7         | 0.08%   |
| 4.18    | 7         | 0.08%   |
| 5.0     | 6         | 0.07%   |
| 6.15    | 4         | 0.05%   |
| 6.10    | 4         | 0.05%   |
| 6.7     | 3         | 0.04%   |
| 6.18    | 2         | 0.02%   |
| 6.14    | 2         | 0.02%   |
| 6.13    | 2         | 0.02%   |
| 6.11    | 2         | 0.02%   |
| 4.15    | 2         | 0.02%   |
| 4.9     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 7461      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 7035      | 93.54%  |
| COSMIC          | 247       | 3.28%   |
| KDE5            | 62        | 0.82%   |
| Unknown         | 55        | 0.73%   |
| KDE             | 25        | 0.33%   |
| X-Cinnamon      | 24        | 0.32%   |
| GNOME Flashback | 13        | 0.17%   |
| XFCE            | 12        | 0.16%   |
| MATE            | 11        | 0.15%   |
| Unity           | 9         | 0.12%   |
| LXQt            | 9         | 0.12%   |
| Cinnamon        | 9         | 0.12%   |
| Budgie          | 4         | 0.05%   |
| awesome         | 3         | 0.04%   |
| KDE6            | 1         | 0.01%   |
| i3              | 1         | 0.01%   |
| Deepin          | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 6942      | 92.2%   |
| Wayland | 547       | 7.27%   |
| Unknown | 29        | 0.39%   |
| Tty     | 11        | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 5509      | 72.82%  |
| GDM3           | 1187      | 15.69%  |
| GDM            | 792       | 10.47%  |
| COSMIC-GREETER | 54        | 0.71%   |
| SDDM           | 14        | 0.19%   |
| TDM            | 5         | 0.07%   |
| LightDM        | 4         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 4263      | 56.58%  |
| pt_BR   | 514       | 6.82%   |
| en_GB   | 499       | 6.62%   |
| de_DE   | 324       | 4.3%    |
| C       | 230       | 3.05%   |
| en_AU   | 180       | 2.39%   |
| fr_FR   | 167       | 2.22%   |
| it_IT   | 157       | 2.08%   |
| es_ES   | 142       | 1.88%   |
| en_CA   | 136       | 1.8%    |
| ru_RU   | 96        | 1.27%   |
| pl_PL   | 85        | 1.13%   |
| pt_PT   | 64        | 0.85%   |
| Unknown | 64        | 0.85%   |
| en_IN   | 46        | 0.61%   |
| sv_SE   | 43        | 0.57%   |
| tr_TR   | 33        | 0.44%   |
| nl_NL   | 32        | 0.42%   |
| es_MX   | 31        | 0.41%   |
| nb_NO   | 28        | 0.37%   |
| en_ZA   | 27        | 0.36%   |
| fi_FI   | 24        | 0.32%   |
| hu_HU   | 23        | 0.31%   |
| en_NZ   | 22        | 0.29%   |
| es_AR   | 19        | 0.25%   |
| en_DK   | 19        | 0.25%   |
| cs_CZ   | 19        | 0.25%   |
| es_CL   | 18        | 0.24%   |
| en_IE   | 16        | 0.21%   |
| fr_CA   | 14        | 0.19%   |
| da_DK   | 14        | 0.19%   |
| zh_CN   | 13        | 0.17%   |
| sk_SK   | 12        | 0.16%   |
| de_CH   | 12        | 0.16%   |
| es_CO   | 11        | 0.15%   |
| de_AT   | 11        | 0.15%   |
| hr_HR   | 8         | 0.11%   |
| zh_TW   | 7         | 0.09%   |
| ro_RO   | 7         | 0.09%   |
| fr_BE   | 7         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 5278      | 69.73%  |
| EFI  | 2291      | 30.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 7141      | 95.34%  |
| Btrfs   | 201       | 2.68%   |
| Overlay | 116       | 1.55%   |
| Xfs     | 23        | 0.31%   |
| Unknown | 7         | 0.09%   |
| Zfs     | 2         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 5460      | 72.38%  |
| GPT     | 1922      | 25.48%  |
| MBR     | 162       | 2.15%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 7286      | 97.34%  |
| Yes       | 199       | 2.66%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6781      | 90.33%  |
| Yes       | 726       | 9.67%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1524      | 20.43%  |
| Dell                   | 1213      | 16.26%  |
| Hewlett-Packard        | 1037      | 13.9%   |
| ASUSTek Computer       | 912       | 12.22%  |
| Acer                   | 569       | 7.63%   |
| Apple                  | 467       | 6.26%   |
| System76               | 272       | 3.65%   |
| MSI                    | 269       | 3.61%   |
| Toshiba                | 129       | 1.73%   |
| Samsung Electronics    | 116       | 1.55%   |
| HUAWEI                 | 100       | 1.34%   |
| Notebook               | 65        | 0.87%   |
| Alienware              | 64        | 0.86%   |
| Google                 | 62        | 0.83%   |
| Sony                   | 58        | 0.78%   |
| Fujitsu                | 37        | 0.5%    |
| Positivo               | 34        | 0.46%   |
| Razer                  | 32        | 0.43%   |
| Unknown                | 27        | 0.36%   |
| Gigabyte Technology    | 26        | 0.35%   |
| PC Specialist          | 24        | 0.32%   |
| Framework              | 23        | 0.31%   |
| Timi                   | 22        | 0.29%   |
| LG Electronics         | 21        | 0.28%   |
| Medion                 | 18        | 0.24%   |
| GPU Company            | 15        | 0.2%    |
| TUXEDO                 | 14        | 0.19%   |
| Packard Bell           | 12        | 0.16%   |
| Avell High Performance | 11        | 0.15%   |
| Chuwi                  | 10        | 0.13%   |
| Eluktronics            | 9         | 0.12%   |
| Teclast                | 8         | 0.11%   |
| Schenker               | 8         | 0.11%   |
| Panasonic              | 8         | 0.11%   |
| HONOR                  | 8         | 0.11%   |
| Gateway                | 8         | 0.11%   |
| Intel                  | 7         | 0.09%   |
| GPD                    | 7         | 0.09%   |
| Clevo                  | 7         | 0.09%   |
| SLIMBOOK               | 6         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| System76 Oryx Pro                    | 62        | 0.83%   |
| Unknown                              | 50        | 0.67%   |
| System76 Lemur Pro                   | 48        | 0.64%   |
| Apple MacBookPro9,2                  | 45        | 0.6%    |
| System76 Gazelle                     | 39        | 0.52%   |
| Dell XPS 15 7590                     | 37        | 0.5%    |
| Apple MacBookAir7,2                  | 37        | 0.5%    |
| Apple MacBookPro8,1                  | 34        | 0.46%   |
| Apple MacBookPro12,1                 | 31        | 0.42%   |
| System76 Darter Pro                  | 30        | 0.4%    |
| System76 Galago Pro                  | 27        | 0.36%   |
| HP Notebook                          | 26        | 0.35%   |
| Apple MacBookPro11,1                 | 25        | 0.34%   |
| Apple MacBookAir6,2                  | 25        | 0.34%   |
| Dell XPS 15 9500                     | 23        | 0.31%   |
| HP Pavilion Notebook                 | 22        | 0.29%   |
| Apple MacBookPro11,3                 | 22        | 0.29%   |
| HP Pavilion dv6                      | 21        | 0.28%   |
| System76 Pangolin                    | 20        | 0.27%   |
| HP Pavilion 15                       | 20        | 0.27%   |
| Dell XPS 15 9570                     | 20        | 0.27%   |
| Dell XPS 15 9560                     | 18        | 0.24%   |
| Apple MacBookPro7,1                  | 17        | 0.23%   |
| Apple MacBookPro10,1                 | 17        | 0.23%   |
| Dell Latitude E6420                  | 16        | 0.21%   |
| Apple MacBookPro5,5                  | 16        | 0.21%   |
| Lenovo Legion 5 15ACH6H 82JU         | 15        | 0.2%    |
| HP Pavilion g6                       | 15        | 0.2%    |
| Dell Inspiron 15 7000 Gaming         | 15        | 0.2%    |
| Apple MacBookPro8,2                  | 15        | 0.2%    |
| Lenovo IdeaPad S145-15API 81V7       | 14        | 0.19%   |
| Dell XPS 13 9370                     | 14        | 0.19%   |
| Apple MacBook5,1                     | 14        | 0.19%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY | 13        | 0.17%   |
| Lenovo IdeaPad 330-15IKB 81FE        | 13        | 0.17%   |
| Lenovo IdeaPad 3 15ALC6 82MF         | 13        | 0.17%   |
| HP Pavilion dv7                      | 13        | 0.17%   |
| HP EliteBook 840 G1                  | 13        | 0.17%   |
| HP Dev One Notebook PC               | 13        | 0.17%   |
| HP 15                                | 13        | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 741       | 9.93%   |
| Lenovo IdeaPad     | 400       | 5.36%   |
| Dell Inspiron      | 375       | 5.03%   |
| Acer Aspire        | 364       | 4.88%   |
| Dell Latitude      | 315       | 4.22%   |
| Dell XPS           | 240       | 3.22%   |
| HP Pavilion        | 235       | 3.15%   |
| ASUS VivoBook      | 173       | 2.32%   |
| HP EliteBook       | 163       | 2.18%   |
| HP Laptop          | 150       | 2.01%   |
| ASUS ROG           | 146       | 1.96%   |
| Lenovo Legion      | 135       | 1.81%   |
| HP ProBook         | 111       | 1.49%   |
| Toshiba Satellite  | 109       | 1.46%   |
| ASUS ASUS          | 108       | 1.45%   |
| Dell Precision     | 97        | 1.3%    |
| Acer Nitro         | 91        | 1.22%   |
| Apple MacBookPro11 | 75        | 1.01%   |
| Dell Vostro        | 73        | 0.98%   |
| System76 Oryx      | 62        | 0.83%   |
| HP OMEN            | 53        | 0.71%   |
| Apple MacBookPro9  | 53        | 0.71%   |
| System76 Lemur     | 52        | 0.7%    |
| ASUS ZenBook       | 50        | 0.67%   |
| Apple MacBookPro8  | 50        | 0.67%   |
| Unknown            | 50        | 0.67%   |
| Acer Swift         | 49        | 0.66%   |
| HP ZBook           | 48        | 0.64%   |
| System76 Gazelle   | 41        | 0.55%   |
| Lenovo ThinkBook   | 41        | 0.55%   |
| HP ENVY            | 41        | 0.55%   |
| Lenovo Yoga        | 39        | 0.52%   |
| ASUS TUF           | 39        | 0.52%   |
| Apple MacBookAir7  | 38        | 0.51%   |
| Apple MacBookPro5  | 33        | 0.44%   |
| Razer Blade        | 32        | 0.43%   |
| HP Victus          | 31        | 0.42%   |
| Apple MacBookPro12 | 31        | 0.42%   |
| Acer Predator      | 31        | 0.42%   |
| System76 Galago    | 30        | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 818       | 10.96%  |
| 2021    | 790       | 10.59%  |
| 2020    | 774       | 10.37%  |
| 2018    | 645       | 8.64%   |
| 2012    | 509       | 6.82%   |
| 2013    | 477       | 6.39%   |
| 2017    | 433       | 5.8%    |
| 2022    | 408       | 5.47%   |
| 2011    | 408       | 5.47%   |
| 2015    | 389       | 5.21%   |
| 2016    | 351       | 4.7%    |
| 2014    | 348       | 4.66%   |
| 2023    | 278       | 3.73%   |
| 2010    | 225       | 3.02%   |
| 2008    | 169       | 2.27%   |
| 2009    | 157       | 2.1%    |
| 2024    | 144       | 1.93%   |
| 2006    | 49        | 0.66%   |
| 2007    | 48        | 0.64%   |
| 2025    | 36        | 0.48%   |
| Unknown | 3         | 0.04%   |
| 2005    | 1         | 0.01%   |
| 2004    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 7461      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 7458      | 99.96%  |
| Enabled  | 3         | 0.04%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 7221      | 96.78%  |
| Yes  | 240       | 3.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2073      | 27.52%  |
| 16.01-24.0  | 1727      | 22.93%  |
| 8.01-16.0   | 1423      | 18.89%  |
| 3.01-4.0    | 966       | 12.82%  |
| 32.01-64.0  | 853       | 11.32%  |
| 64.01-256.0 | 198       | 2.63%   |
| 24.01-32.0  | 161       | 2.14%   |
| 1.01-2.0    | 83        | 1.1%    |
| 2.01-3.0    | 49        | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 2299      | 28.25%  |
| 2.01-3.0   | 2152      | 26.45%  |
| 3.01-4.0   | 1525      | 18.74%  |
| 1.01-2.0   | 1431      | 17.59%  |
| 8.01-16.0  | 615       | 7.56%   |
| 16.01-24.0 | 77        | 0.95%   |
| 24.01-32.0 | 22        | 0.27%   |
| 0.51-1.0   | 12        | 0.15%   |
| 32.01-64.0 | 3         | 0.04%   |
| 0.01-0.5   | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5320      | 70.07%  |
| 2      | 1941      | 25.57%  |
| 3      | 245       | 3.23%   |
| 4      | 39        | 0.51%   |
| 0      | 36        | 0.47%   |
| 5      | 9         | 0.12%   |
| 7      | 1         | 0.01%   |
| 6      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5608      | 74.98%  |
| Yes       | 1871      | 25.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5882      | 78.35%  |
| No        | 1625      | 21.65%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7258      | 97.23%  |
| No        | 207       | 2.77%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6440      | 85.6%   |
| No        | 1083      | 14.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 1958      | 26.1%   |
| Brazil       | 705       | 9.4%    |
| Germany      | 466       | 6.21%   |
| UK           | 306       | 4.08%   |
| India        | 296       | 3.95%   |
| Canada       | 277       | 3.69%   |
| Italy        | 260       | 3.47%   |
| France       | 236       | 3.15%   |
| Australia    | 206       | 2.75%   |
| Netherlands  | 154       | 2.05%   |
| Russia       | 143       | 1.91%   |
| Poland       | 141       | 1.88%   |
| Spain        | 140       | 1.87%   |
| Sweden       | 113       | 1.51%   |
| Mexico       | 104       | 1.39%   |
| Portugal     | 101       | 1.35%   |
| Turkey       | 76        | 1.01%   |
| Norway       | 75        | 1%      |
| Romania      | 74        | 0.99%   |
| Indonesia    | 72        | 0.96%   |
| Switzerland  | 69        | 0.92%   |
| South Africa | 66        | 0.88%   |
| Finland      | 62        | 0.83%   |
| Czechia      | 62        | 0.83%   |
| Denmark      | 60        | 0.8%    |
| Philippines  | 58        | 0.77%   |
| Belgium      | 54        | 0.72%   |
| New Zealand  | 51        | 0.68%   |
| Austria      | 50        | 0.67%   |
| Argentina    | 47        | 0.63%   |
| Hungary      | 46        | 0.61%   |
| Greece       | 45        | 0.6%    |
| Chile        | 43        | 0.57%   |
| Bulgaria     | 35        | 0.47%   |
| Ireland      | 34        | 0.45%   |
| Colombia     | 31        | 0.41%   |
| Croatia      | 30        | 0.4%    |
| Serbia       | 28        | 0.37%   |
| Malaysia     | 28        | 0.37%   |
| Japan        | 28        | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 81        | 1.02%   |
| Melbourne      | 58        | 0.73%   |
| Sydney         | 50        | 0.63%   |
| Milan          | 50        | 0.63%   |
| Warsaw         | 46        | 0.58%   |
| Brisbane       | 46        | 0.58%   |
| Bengaluru      | 44        | 0.56%   |
| Paris          | 39        | 0.49%   |
| Helsinki       | 38        | 0.48%   |
| Berlin         | 38        | 0.48%   |
| New York       | 36        | 0.46%   |
| Moscow         | 36        | 0.46%   |
| Madrid         | 36        | 0.46%   |
| Rio de Janeiro | 35        | 0.44%   |
| Chicago        | 34        | 0.43%   |
| Istanbul       | 33        | 0.42%   |
| Vienna         | 31        | 0.39%   |
| Dallas         | 31        | 0.39%   |
| Rome           | 28        | 0.35%   |
| Los Angeles    | 28        | 0.35%   |
| Bucharest      | 28        | 0.35%   |
| Amsterdam      | 28        | 0.35%   |
| Auckland       | 27        | 0.34%   |
| Toronto        | 26        | 0.33%   |
| London         | 26        | 0.33%   |
| Seattle        | 25        | 0.32%   |
| Prague         | 25        | 0.32%   |
| Oslo           | 25        | 0.32%   |
| Mexico City    | 25        | 0.32%   |
| Denver         | 25        | 0.32%   |
| Lisbon         | 24        | 0.3%    |
| Sofia          | 23        | 0.29%   |
| Johannesburg   | 23        | 0.29%   |
| St Petersburg  | 22        | 0.28%   |
| Porto Alegre   | 22        | 0.28%   |
| Jakarta        | 22        | 0.28%   |
| Brasília      | 22        | 0.28%   |
| Athens         | 22        | 0.28%   |
| Stockholm      | 21        | 0.27%   |
| Fortaleza      | 20        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 1782      | 2419   | 18.51%  |
| WDC                            | 889       | 1034   | 9.23%   |
| Seagate                        | 788       | 932    | 8.18%   |
| Sandisk                        | 769       | 1006   | 7.99%   |
| Toshiba                        | 548       | 650    | 5.69%   |
| SK hynix                       | 504       | 626    | 5.23%   |
| Kingston                       | 485       | 587    | 5.04%   |
| Unknown                        | 394       | 483    | 4.09%   |
| Micron Technology              | 348       | 403    | 3.61%   |
| Intel                          | 323       | 401    | 3.35%   |
| Crucial                        | 320       | 386    | 3.32%   |
| Apple                          | 246       | 274    | 2.56%   |
| HGST                           | 241       | 277    | 2.5%    |
| Hitachi                        | 134       | 148    | 1.39%   |
| KIOXIA                         | 126       | 151    | 1.31%   |
| A-DATA Technology              | 122       | 147    | 1.27%   |
| Phison                         | 95        | 122    | 0.99%   |
| Micron/Crucial Technology      | 86        | 107    | 0.89%   |
| China                          | 80        | 91     | 0.83%   |
| Silicon Motion                 | 74        | 91     | 0.77%   |
| PNY                            | 63        | 76     | 0.65%   |
| LITEON                         | 63        | 75     | 0.65%   |
| Phison Electronics             | 55        | 69     | 0.57%   |
| Kingston Technology Company    | 52        | 56     | 0.54%   |
| ADATA Technology               | 49        | 60     | 0.51%   |
| Transcend                      | 46        | 53     | 0.48%   |
| LITEONIT                       | 36        | 54     | 0.37%   |
| Unknown                        | 36        | 40     | 0.37%   |
| SPCC                           | 35        | 37     | 0.36%   |
| Team                           | 29        | 34     | 0.3%    |
| KingSpec                       | 28        | 32     | 0.29%   |
| JMicron Technology             | 27        | 35     | 0.28%   |
| ASMT                           | 26        | 28     | 0.27%   |
| Patriot                        | 25        | 29     | 0.26%   |
| MAXIO Technology (Hangzhou)    | 25        | 26     | 0.26%   |
| Intenso                        | 23        | 33     | 0.24%   |
| Solid State Storage Technology | 21        | 25     | 0.22%   |
| Union Memory (Shenzhen)        | 20        | 24     | 0.21%   |
| Fujitsu                        | 20        | 21     | 0.21%   |
| Netac                          | 19        | 25     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 144       | 1.43%   |
| Seagate ST1000LM035-1RK172 1TB                       | 134       | 1.33%   |
| Kingston SA400S37240G 240GB SSD                      | 115       | 1.14%   |
| HGST HTS721010A9E630 1TB                             | 107       | 1.06%   |
| Unknown MMC Card  64GB                               | 85        | 0.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB   | 84        | 0.83%   |
| Samsung NVMe SSD Drive 512GB                         | 80        | 0.79%   |
| Toshiba MQ01ABD100 1TB                               | 75        | 0.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 71        | 0.71%   |
| SanDisk NVMe SSD Drive 1TB                           | 68        | 0.68%   |
| Unknown MMC Card  32GB                               | 67        | 0.67%   |
| Toshiba MQ04ABF100 1TB                               | 66        | 0.66%   |
| SanDisk NVMe SSD Drive 512GB                         | 66        | 0.66%   |
| Samsung NVMe SSD Drive 1TB                           | 64        | 0.64%   |
| SK hynix NVMe SSD Drive 512GB                        | 59        | 0.59%   |
| Samsung NVMe SSD Drive 256GB                         | 57        | 0.57%   |
| Kingston SA400S37480G 480GB SSD                      | 53        | 0.53%   |
| Samsung NVMe SSD Drive 500GB                         | 52        | 0.52%   |
| Samsung SSD 860 EVO 500GB                            | 48        | 0.48%   |
| WDC WD10SPZX-24Z10 1TB                               | 47        | 0.47%   |
| Intel NVMe SSD Drive 512GB                           | 47        | 0.47%   |
| Unknown MMC Card  128GB                              | 46        | 0.46%   |
| Seagate ST500LT012-1DG142 500GB                      | 44        | 0.44%   |
| Seagate ST9500325AS 500GB                            | 43        | 0.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB | 42        | 0.42%   |
| Seagate ST1000LM049-2GH172 1TB                       | 41        | 0.41%   |
| Apple SSD SM0128G 121GB                              | 41        | 0.41%   |
| Samsung NVMe SSD Drive 1024GB                        | 40        | 0.4%    |
| Crucial CT500MX500SSD1 500GB                         | 40        | 0.4%    |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                | 39        | 0.39%   |
| SanDisk NVMe SSD Drive 256GB                         | 39        | 0.39%   |
| WDC WD10SPZX-21Z10T0 1TB                             | 38        | 0.38%   |
| Crucial CT240BX500SSD1 240GB                         | 38        | 0.38%   |
| Crucial CT1000MX500SSD1 1TB                          | 38        | 0.38%   |
| Samsung SSD 850 EVO 500GB                            | 36        | 0.36%   |
| HGST HTS541010A9E680 1TB                             | 36        | 0.36%   |
| Unknown                                              | 36        | 0.36%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB     | 35        | 0.35%   |
| Samsung SSD 850 EVO 250GB                            | 35        | 0.35%   |
| Toshiba MQ01ABF050 500GB                             | 34        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 753       | 879    | 35.07%  |
| WDC                 | 524       | 588    | 24.41%  |
| Toshiba             | 337       | 383    | 15.7%   |
| HGST                | 241       | 277    | 11.22%  |
| Hitachi             | 134       | 148    | 6.24%   |
| Samsung Electronics | 39        | 40     | 1.82%   |
| Unknown             | 28        | 31     | 1.3%    |
| Apple               | 21        | 24     | 0.98%   |
| Fujitsu             | 20        | 21     | 0.93%   |
| JMicron Technology  | 13        | 18     | 0.61%   |
| TO Exter            | 7         | 7      | 0.33%   |
| External            | 5         | 5      | 0.23%   |
| ASMT                | 5         | 7      | 0.23%   |
| Intenso             | 4         | 10     | 0.19%   |
| MaxDigital          | 2         | 2      | 0.09%   |
| Inateck             | 2         | 2      | 0.09%   |
| USB3.0              | 1         | 1      | 0.05%   |
| T-FORCE             | 1         | 1      | 0.05%   |
| StoreJet            | 1         | 1      | 0.05%   |
| SATAFIRM            | 1         | 1      | 0.05%   |
| SABRENT             | 1         | 2      | 0.05%   |
| RSH-339             | 1         | 1      | 0.05%   |
| Min Yi U            | 1         | 1      | 0.05%   |
| KESU                | 1         | 1      | 0.05%   |
| HGST HDN            | 1         | 1      | 0.05%   |
| DAS                 | 1         | 4      | 0.05%   |
| ASMedia             | 1         | 1      | 0.05%   |
| Asm                 | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 632       | 820    | 20.66%  |
| Kingston            | 358       | 415    | 11.7%   |
| SanDisk             | 292       | 363    | 9.55%   |
| Crucial             | 284       | 341    | 9.28%   |
| Apple               | 192       | 212    | 6.28%   |
| WDC                 | 187       | 231    | 6.11%   |
| SK hynix            | 82        | 92     | 2.68%   |
| China               | 80        | 91     | 2.62%   |
| A-DATA Technology   | 79        | 93     | 2.58%   |
| Micron Technology   | 74        | 81     | 2.42%   |
| Toshiba             | 68        | 80     | 2.22%   |
| Intel               | 64        | 69     | 2.09%   |
| PNY                 | 60        | 72     | 1.96%   |
| LITEON              | 58        | 70     | 1.9%    |
| Transcend           | 43        | 50     | 1.41%   |
| LITEONIT            | 36        | 54     | 1.18%   |
| SPCC                | 32        | 34     | 1.05%   |
| KingSpec            | 25        | 28     | 0.82%   |
| Patriot             | 23        | 26     | 0.75%   |
| Team                | 18        | 23     | 0.59%   |
| Netac               | 18        | 22     | 0.59%   |
| Intenso             | 17        | 21     | 0.56%   |
| Seagate             | 16        | 17     | 0.52%   |
| OCZ                 | 15        | 15     | 0.49%   |
| Lexar               | 14        | 16     | 0.46%   |
| Hewlett-Packard     | 13        | 15     | 0.42%   |
| SABRENT             | 12        | 14     | 0.39%   |
| Corsair             | 12        | 13     | 0.39%   |
| Apacer              | 11        | 16     | 0.36%   |
| KingDian            | 9         | 10     | 0.29%   |
| Verbatim            | 8         | 10     | 0.26%   |
| KIOXIA-EXCERIA      | 8         | 8      | 0.26%   |
| GOODRAM             | 8         | 9      | 0.26%   |
| Dogfish             | 8         | 12     | 0.26%   |
| BHT                 | 8         | 8      | 0.26%   |
| Unknown             | 8         | 8      | 0.26%   |
| Plextor             | 7         | 9      | 0.23%   |
| Gigabyte Technology | 6         | 8      | 0.2%    |
| Teclast             | 5         | 6      | 0.16%   |
| FORESEE             | 5         | 6      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 3600      | 5125   | 40.11%  |
| SSD     | 2834      | 3664   | 31.58%  |
| HDD     | 2071      | 2458   | 23.08%  |
| MMC     | 332       | 403    | 3.7%    |
| Unknown | 138       | 170    | 1.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4279      | 5862   | 49.96%  |
| NVMe | 3592      | 5088   | 41.94%  |
| SAS  | 362       | 467    | 4.23%   |
| MMC  | 332       | 403    | 3.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3082      | 3943   | 63.07%  |
| 0.51-1.0   | 1543      | 1848   | 31.57%  |
| 1.01-2.0   | 208       | 260    | 4.26%   |
| 3.01-4.0   | 35        | 46     | 0.72%   |
| 4.01-10.0  | 11        | 15     | 0.23%   |
| 2.01-3.0   | 5         | 5      | 0.1%    |
| 10.01-20.0 | 2         | 4      | 0.04%   |
| 20.01-50.0 | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 2514      | 32.57%  |
| 251-500        | 2224      | 28.82%  |
| 501-1000       | 1479      | 19.16%  |
| 1001-2000      | 556       | 7.2%    |
| 51-100         | 341       | 4.42%   |
| 1-20           | 166       | 2.15%   |
| 21-50          | 151       | 1.96%   |
| 2001-3000      | 123       | 1.59%   |
| More than 3000 | 118       | 1.53%   |
| Unknown        | 46        | 0.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2916      | 35.86%  |
| 21-50          | 1887      | 23.21%  |
| 101-250        | 1126      | 13.85%  |
| 51-100         | 1043      | 12.83%  |
| 251-500        | 609       | 7.49%   |
| 501-1000       | 333       | 4.1%    |
| 1001-2000      | 114       | 1.4%    |
| Unknown        | 46        | 0.57%   |
| More than 3000 | 32        | 0.39%   |
| 2001-3000      | 25        | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 8         | 8      | 4.57%   |
| HGST HTS725050A7E630 500GB            | 5         | 8      | 2.86%   |
| HGST HTS541010A9E680 1TB              | 5         | 5      | 2.86%   |
| SK hynix PC711 HFS001TDE9X073N 1TB    | 4         | 4      | 2.29%   |
| Seagate ST500LT012-9WS142 500GB       | 4         | 4      | 2.29%   |
| Seagate ST1000LX015-1U7172 1TB        | 4         | 4      | 2.29%   |
| HGST HTS721010A9E630 1TB              | 4         | 4      | 2.29%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 1.71%   |
| Seagate ST1000LM049-2GH172 1TB        | 3         | 3      | 1.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 3      | 1.71%   |
| Hitachi HTS545050A7E380 500GB         | 3         | 5      | 1.71%   |
| HGST HTS545050A7E680 500GB            | 3         | 3      | 1.71%   |
| WDC WD10JPCX-24UE4T0 1TB              | 2         | 2      | 1.14%   |
| Toshiba MK7559GSXP 752GB              | 2         | 2      | 1.14%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 2         | 2      | 1.14%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 2      | 1.14%   |
| Seagate ST9500325AS 500GB             | 2         | 3      | 1.14%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 2      | 1.14%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 2         | 2      | 1.14%   |
| Kingston SUV400S37120G 120GB SSD      | 2         | 2      | 1.14%   |
| Kingston SA400S37240G 240GB SSD       | 2         | 2      | 1.14%   |
| Intel SSDSCKKF256G8H 256GB            | 2         | 2      | 1.14%   |
| Crucial CT525MX300SSD1 528GB          | 2         | 2      | 1.14%   |
| Crucial CT1000P1SSD8 1TB              | 2         | 2      | 1.14%   |
| XPG GAMMIX S41 512GB                  | 1         | 1      | 0.57%   |
| WHALEKOM SSD 512GB                    | 1         | 1      | 0.57%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD      | 1         | 2      | 0.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.57%   |
| WDC WDS200T2B0B-00YS70 2TB SSD        | 1         | 1      | 0.57%   |
| WDC WDS100T2G0A-00JH30 1TB SSD        | 1         | 1      | 0.57%   |
| WDC WDS100T2B0B-00YS70 1TB SSD        | 1         | 1      | 0.57%   |
| WDC WD5000LPVX-75V0TT0 500GB          | 1         | 1      | 0.57%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 0.57%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 1         | 1      | 0.57%   |
| WDC WD5000LPCX-21VHAT0 500GB          | 1         | 1      | 0.57%   |
| WDC WD5000BPVT-22HXZT3 500GB          | 1         | 1      | 0.57%   |
| WDC WD5000BPVT-08HXZT3 500GB          | 1         | 1      | 0.57%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 0.57%   |
| WDC WD3200BEKX-75B7WT0 320GB          | 1         | 1      | 0.57%   |
| WDC WD3200BEKT-60PVMT0 320GB          | 1         | 1      | 0.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 37     | 20.57%  |
| WDC                 | 30        | 31     | 17.14%  |
| HGST                | 18        | 21     | 10.29%  |
| Toshiba             | 14        | 15     | 8%      |
| SK hynix            | 14        | 16     | 8%      |
| Samsung Electronics | 10        | 10     | 5.71%   |
| Hitachi             | 7         | 9      | 4%      |
| Crucial             | 7         | 7      | 4%      |
| A-DATA Technology   | 7         | 7      | 4%      |
| Kingston            | 6         | 6      | 3.43%   |
| Intel               | 6         | 6      | 3.43%   |
| Micron Technology   | 4         | 4      | 2.29%   |
| SanDisk             | 3         | 3      | 1.71%   |
| XPG                 | 1         | 1      | 0.57%   |
| WHALEKOM            | 1         | 1      | 0.57%   |
| Team                | 1         | 1      | 0.57%   |
| SSSTC               | 1         | 1      | 0.57%   |
| SPCC                | 1         | 1      | 0.57%   |
| Silicon Motion      | 1         | 1      | 0.57%   |
| LITEON              | 1         | 1      | 0.57%   |
| Lexar               | 1         | 1      | 0.57%   |
| Leven               | 1         | 1      | 0.57%   |
| Hewlett-Packard     | 1         | 1      | 0.57%   |
| China               | 1         | 1      | 0.57%   |
| ASMT                | 1         | 1      | 0.57%   |
| Apacer              | 1         | 1      | 0.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 36        | 37     | 37.5%   |
| WDC     | 23        | 23     | 23.96%  |
| HGST    | 18        | 21     | 18.75%  |
| Toshiba | 11        | 11     | 11.46%  |
| Hitachi | 7         | 9      | 7.29%   |
| ASMT    | 1         | 1      | 1.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 96        | 102    | 54.86%  |
| SSD  | 46        | 50     | 26.29%  |
| NVMe | 33        | 33     | 18.86%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB | 1         | 1      | 50%     |
| Intenso JAJP600M1TB               | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Intenso             | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 5683      | 8981   | 72.75%  |
| Works    | 1953      | 2652   | 25%     |
| Malfunc  | 174       | 185    | 2.23%   |
| Failed   | 2         | 2      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 4689      | 49.36%  |
| Samsung Electronics                     | 1281      | 13.48%  |
| AMD                                     | 835       | 8.79%   |
| SanDisk                                 | 640       | 6.74%   |
| SK hynix                                | 421       | 4.43%   |
| Micron Technology                       | 278       | 2.93%   |
| Kingston Technology Company             | 178       | 1.87%   |
| Toshiba America Info Systems            | 161       | 1.69%   |
| Phison Electronics                      | 156       | 1.64%   |
| KIOXIA                                  | 121       | 1.27%   |
| Micron/Crucial Technology               | 110       | 1.16%   |
| Nvidia                                  | 105       | 1.11%   |
| ADATA Technology                        | 93        | 0.98%   |
| Silicon Motion                          | 92        | 0.97%   |
| Solid State Storage Technology          | 54        | 0.57%   |
| MAXIO Technology (Hangzhou)             | 39        | 0.41%   |
| Union Memory (Shenzhen)                 | 36        | 0.38%   |
| Apple                                   | 33        | 0.35%   |
| Marvell Technology Group                | 32        | 0.34%   |
| Realtek Semiconductor                   | 26        | 0.27%   |
| Shenzhen Longsys Electronics            | 19        | 0.2%    |
| Solidigm                                | 16        | 0.17%   |
| Seagate Technology                      | 13        | 0.14%   |
| Lite-On Technology                      | 9         | 0.09%   |
| Lenovo                                  | 9         | 0.09%   |
| Yangtze Memory Technologies             | 8         | 0.08%   |
| Silicon Integrated Systems [SiS]        | 8         | 0.08%   |
| INNOGRIT                                | 8         | 0.08%   |
| JMicron Technology                      | 5         | 0.05%   |
| ASMedia Technology                      | 5         | 0.05%   |
| Silicon Image                           | 3         | 0.03%   |
| Shenzhen Unionmemory Information System | 3         | 0.03%   |
| Hosin Global Electronics                | 3         | 0.03%   |
| Transcend                               | 2         | 0.02%   |
| OCZ Technology Group                    | 2         | 0.02%   |
| O2 Micro                                | 2         | 0.02%   |
| Netac Technology                        | 2         | 0.02%   |
| Biwin Storage Technology                | 2         | 0.02%   |
| Enmotus                                 | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 787       | 7.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 561       | 5.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 531       | 5.34%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 460       | 4.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 417       | 4.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 380       | 3.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 318       | 3.2%    |
| Intel Volume Management Device NVMe RAID Controller                            | 281       | 2.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 257       | 2.58%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 217       | 2.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 217       | 2.18%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 206       | 2.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 202       | 2.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 188       | 1.89%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 154       | 1.55%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 129       | 1.3%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 128       | 1.29%   |
| Intel SSD 660P Series                                                          | 124       | 1.25%   |
| Intel Comet Lake SATA AHCI Controller                                          | 121       | 1.22%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 121       | 1.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 119       | 1.2%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 117       | 1.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 106       | 1.07%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 95        | 0.95%   |
| Intel Tiger Lake-LP SATA Controller                                            | 79        | 0.79%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 77        | 0.77%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 75        | 0.75%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 75        | 0.75%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 71        | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 71        | 0.71%   |
| Phison E12 NVMe Controller                                                     | 68        | 0.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 68        | 0.68%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 67        | 0.67%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 67        | 0.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 66        | 0.66%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 61        | 0.61%   |
| Nvidia MCP79 AHCI Controller                                                   | 60        | 0.6%    |
| Intel SSD 670p Series [Keystone Harbor]                                        | 60        | 0.6%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 60        | 0.6%    |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 59        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 4837      | 51.29%  |
| NVMe | 3583      | 38%     |
| RAID | 803       | 8.52%   |
| IDE  | 207       | 2.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 5939      | 79.59%  |
| AMD    | 1523      | 20.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 161       | 2.16%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 136       | 1.82%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 128       | 1.71%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 126       | 1.69%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 117       | 1.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 110       | 1.47%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 101       | 1.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 93        | 1.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 92        | 1.23%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 91        | 1.22%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 87        | 1.17%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 83        | 1.11%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 82        | 1.1%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 81        | 1.09%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 79        | 1.06%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 78        | 1.05%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 75        | 1%      |
| AMD Ryzen 7 5800H with Radeon Graphics        | 74        | 0.99%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 73        | 0.98%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 72        | 0.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 65        | 0.87%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 59        | 0.79%   |
| Intel 12th Gen Core i7-12700H                 | 58        | 0.78%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 57        | 0.76%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 55        | 0.74%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 53        | 0.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 52        | 0.7%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 52        | 0.7%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 49        | 0.66%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 47        | 0.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 45        | 0.6%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 44        | 0.59%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 44        | 0.59%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 43        | 0.58%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 43        | 0.58%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 42        | 0.56%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 42        | 0.56%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 41        | 0.55%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 41        | 0.55%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 41        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 2015      | 27%     |
| Intel Core i5           | 1795      | 24.06%  |
| Other                   | 907       | 12.15%  |
| AMD Ryzen 7             | 476       | 6.38%   |
| Intel Core i3           | 425       | 5.7%    |
| AMD Ryzen 5             | 420       | 5.63%   |
| Intel Core 2 Duo        | 229       | 3.07%   |
| Intel Celeron           | 224       | 3%      |
| AMD Ryzen 9             | 108       | 1.45%   |
| Intel Core i9           | 78        | 1.05%   |
| AMD Ryzen 3             | 75        | 1.01%   |
| Intel Pentium           | 70        | 0.94%   |
| AMD Ryzen 7 PRO         | 64        | 0.86%   |
| AMD A6                  | 63        | 0.84%   |
| Intel Core              | 55        | 0.74%   |
| AMD A8                  | 45        | 0.6%    |
| Intel Pentium Dual-Core | 41        | 0.55%   |
| AMD A10                 | 39        | 0.52%   |
| AMD A4                  | 36        | 0.48%   |
| AMD Ryzen 5 PRO         | 32        | 0.43%   |
| Intel Atom              | 22        | 0.29%   |
| Intel Xeon              | 21        | 0.28%   |
| AMD Athlon              | 19        | 0.25%   |
| Intel Core 2            | 18        | 0.24%   |
| Intel Core m3           | 16        | 0.21%   |
| Intel Pentium Dual      | 15        | 0.2%    |
| Intel Genuine           | 14        | 0.19%   |
| AMD E1                  | 14        | 0.19%   |
| Intel Core M            | 12        | 0.16%   |
| AMD E                   | 12        | 0.16%   |
| Intel Pentium Silver    | 11        | 0.15%   |
| AMD E2                  | 10        | 0.13%   |
| AMD A12                 | 10        | 0.13%   |
| AMD FX                  | 9         | 0.12%   |
| AMD Turion 64 X2 Mobile | 7         | 0.09%   |
| Intel Core m5           | 5         | 0.07%   |
| AMD Athlon X2           | 5         | 0.07%   |
| Intel Celeron Dual-Core | 4         | 0.05%   |
| AMD C-60                | 4         | 0.05%   |
| AMD Athlon 64 X2        | 4         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2883      | 38.64%  |
| 4      | 2504      | 33.56%  |
| 8      | 824       | 11.04%  |
| 6      | 769       | 10.31%  |
| 14     | 150       | 2.01%   |
| 10     | 109       | 1.46%   |
| 12     | 80        | 1.07%   |
| 16     | 61        | 0.82%   |
| 24     | 47        | 0.63%   |
| 1      | 30        | 0.4%    |
| 3      | 2         | 0.03%   |
| 20     | 1         | 0.01%   |
| 7      | 1         | 0.01%   |
| 5      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 7454      | 99.91%  |
| 2      | 6         | 0.08%   |
| 24     | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 6385      | 85.53%  |
| 1      | 1080      | 14.47%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7454      | 99.91%  |
| Unknown        | 7         | 0.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 5707      | 74.92%  |
| 0x906ea    | 153       | 2.01%   |
| 0x806ea    | 109       | 1.43%   |
| 0x306a9    | 103       | 1.35%   |
| 0x806ec    | 98        | 1.29%   |
| 0x806c1    | 94        | 1.23%   |
| 0x206a7    | 93        | 1.22%   |
| 0x406e3    | 87        | 1.14%   |
| 0x40651    | 80        | 1.05%   |
| 0xa0652    | 75        | 0.98%   |
| 0x806e9    | 62        | 0.81%   |
| 0x0a50000c | 62        | 0.81%   |
| 0x306c3    | 57        | 0.75%   |
| 0x906e9    | 53        | 0.7%    |
| 0x08108102 | 48        | 0.63%   |
| 0x08600106 | 41        | 0.54%   |
| 0x306d4    | 40        | 0.53%   |
| 0x806d1    | 37        | 0.49%   |
| 0x1067a    | 35        | 0.46%   |
| 0x806eb    | 34        | 0.45%   |
| 0x506e3    | 34        | 0.45%   |
| 0x08108109 | 33        | 0.43%   |
| 0x08608103 | 29        | 0.38%   |
| 0x906ed    | 28        | 0.37%   |
| 0x08600104 | 26        | 0.34%   |
| 0x906a3    | 25        | 0.33%   |
| 0x20655    | 22        | 0.29%   |
| 0x706e5    | 20        | 0.26%   |
| 0x0a404102 | 20        | 0.26%   |
| 0x08600103 | 20        | 0.26%   |
| 0x06006705 | 18        | 0.24%   |
| 0x0810100b | 16        | 0.21%   |
| 0x0a50000d | 14        | 0.18%   |
| 0x706a1    | 13        | 0.17%   |
| 0x0a404101 | 13        | 0.17%   |
| 0x40661    | 11        | 0.14%   |
| 0x10676    | 11        | 0.14%   |
| 0x07030105 | 10        | 0.13%   |
| 0xa0660    | 9         | 0.12%   |
| 0x906a4    | 9         | 0.12%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| KabyLake           | 1621      | 21.69%  |
| Unknown            | 718       | 9.61%   |
| Haswell            | 619       | 8.28%   |
| IvyBridge          | 478       | 6.39%   |
| SandyBridge        | 471       | 6.3%    |
| Skylake            | 411       | 5.5%    |
| TigerLake          | 336       | 4.49%   |
| Zen 3              | 285       | 3.81%   |
| Broadwell          | 281       | 3.76%   |
| Zen+               | 268       | 3.59%   |
| CometLake          | 264       | 3.53%   |
| Zen 2              | 244       | 3.26%   |
| Penryn             | 243       | 3.25%   |
| Westmere           | 177       | 2.37%   |
| Alderlake Hybrid   | 177       | 2.37%   |
| IceLake            | 149       | 1.99%   |
| Silvermont         | 96        | 1.28%   |
| Excavator          | 90        | 1.2%    |
| Core               | 87        | 1.16%   |
| Goldmont plus      | 84        | 1.12%   |
| Zen                | 70        | 0.94%   |
| Puma               | 52        | 0.7%    |
| Piledriver         | 42        | 0.56%   |
| Goldmont           | 32        | 0.43%   |
| Bobcat             | 28        | 0.37%   |
| Nehalem            | 20        | 0.27%   |
| K10 Llano          | 20        | 0.27%   |
| Jaguar             | 20        | 0.27%   |
| Steamroller        | 18        | 0.24%   |
| Meteorlake Hybrid  | 16        | 0.21%   |
| K8 Hammer          | 16        | 0.21%   |
| K10                | 12        | 0.16%   |
| K8 & K10 hybrid    | 11        | 0.15%   |
| Gracemont          | 6         | 0.08%   |
| Tremont            | 4         | 0.05%   |
| Bonnell            | 4         | 0.05%   |
| Lunarlake Hybrid   | 3         | 0.04%   |
| ArrowLake-H Hybrid | 2         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5430      | 54.01%  |
| Nvidia                           | 2777      | 27.62%  |
| AMD                              | 1839      | 18.29%  |
| Silicon Integrated Systems [SiS] | 6         | 0.06%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 439       | 4.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 428       | 4.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 427       | 4.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 331       | 3.22%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                              | 311       | 3.03%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 309       | 3.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 271       | 2.64%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                 | 246       | 2.4%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 239       | 2.33%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                           | 232       | 2.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 230       | 2.24%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 219       | 2.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 210       | 2.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 205       | 2%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 193       | 1.88%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                              | 189       | 1.84%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                               | 187       | 1.82%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                               | 167       | 1.63%   |
| Intel Core Processor Integrated Graphics Controller                                   | 134       | 1.3%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 133       | 1.29%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 128       | 1.25%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 126       | 1.23%   |
| AMD Lucienne                                                                          | 115       | 1.12%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 106       | 1.03%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                 | 105       | 1.02%   |
| AMD Rembrandt [Radeon 680M]                                                           | 105       | 1.02%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 96        | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 93        | 0.91%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 83        | 0.81%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 81        | 0.79%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 79        | 0.77%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 78        | 0.76%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 76        | 0.74%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 74        | 0.72%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                       | 73        | 0.71%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 71        | 0.69%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 69        | 0.67%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 67        | 0.65%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 67        | 0.65%   |
| Nvidia GP108M [GeForce MX150]                                                         | 64        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 3298      | 43.89%  |
| Intel + Nvidia     | 1872      | 24.91%  |
| 1 x AMD            | 1036      | 13.79%  |
| 1 x Nvidia         | 472       | 6.28%   |
| AMD + Nvidia       | 404       | 5.38%   |
| Intel + AMD        | 262       | 3.49%   |
| 2 x AMD            | 140       | 1.86%   |
| 2 x Nvidia         | 13        | 0.17%   |
| Other              | 6         | 0.08%   |
| 1 x SiS            | 6         | 0.08%   |
| 2 x Intel          | 2         | 0.03%   |
| Intel + 2 x Nvidia | 2         | 0.03%   |
| 1 x S3 Graphics    | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 5516      | 73.09%  |
| Proprietary | 1778      | 23.56%  |
| Unknown     | 253       | 3.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 6001      | 79.17%  |
| 1.01-2.0   | 393       | 5.18%   |
| 3.01-4.0   | 350       | 4.62%   |
| 0.01-0.5   | 343       | 4.53%   |
| 5.01-6.0   | 206       | 2.72%   |
| 7.01-8.0   | 125       | 1.65%   |
| 0.51-1.0   | 112       | 1.48%   |
| 2.01-3.0   | 31        | 0.41%   |
| 8.01-16.0  | 19        | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1535      | 17.62%  |
| Chimei Innolux          | 1259      | 14.45%  |
| BOE                     | 1258      | 14.44%  |
| LG Display              | 1132      | 13%     |
| Samsung Electronics     | 768       | 8.82%   |
| Apple                   | 407       | 4.67%   |
| Sharp                   | 284       | 3.26%   |
| Dell                    | 254       | 2.92%   |
| Goldstar                | 251       | 2.88%   |
| PANDA                   | 198       | 2.27%   |
| Chi Mei Optoelectronics | 130       | 1.49%   |
| Lenovo                  | 122       | 1.4%    |
| AOC                     | 91        | 1.04%   |
| Hewlett-Packard         | 88        | 1.01%   |
| Acer                    | 88        | 1.01%   |
| InfoVision              | 77        | 0.88%   |
| Philips                 | 70        | 0.8%    |
| BenQ                    | 57        | 0.65%   |
| CSO                     | 53        | 0.61%   |
| ASUSTek Computer        | 50        | 0.57%   |
| Ancor Communications    | 43        | 0.49%   |
| ViewSonic               | 30        | 0.34%   |
| TMX                     | 30        | 0.34%   |
| Iiyama                  | 22        | 0.25%   |
| LG Philips              | 21        | 0.24%   |
| Sony                    | 18        | 0.21%   |
| Panasonic               | 15        | 0.17%   |
| MSI                     | 13        | 0.15%   |
| CSW                     | 13        | 0.15%   |
| Vizio                   | 12        | 0.14%   |
| Toshiba                 | 12        | 0.14%   |
| HKC                     | 12        | 0.14%   |
| InnoLux Display         | 11        | 0.13%   |
| CSOT                    | 11        | 0.13%   |
| RTK                     | 10        | 0.11%   |
| JDI                     | 10        | 0.11%   |
| Vestel Elektronik       | 9         | 0.1%    |
| Sceptre Tech            | 8         | 0.09%   |
| Gigabyte Technology     | 8         | 0.09%   |
| Hitachi                 | 7         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 79        | 0.9%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 76        | 0.86%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 71        | 0.81%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 64        | 0.73%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 64        | 0.73%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 62        | 0.7%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 56        | 0.64%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 48        | 0.55%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 44        | 0.5%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 42        | 0.48%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 37        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 35        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 35        | 0.4%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 34        | 0.39%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 31        | 0.35%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch      | 30        | 0.34%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 30        | 0.34%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 29        | 0.33%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 29        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 28        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 28        | 0.32%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 27        | 0.31%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch               | 26        | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 26        | 0.3%    |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                      | 26        | 0.3%    |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 24        | 0.27%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch           | 23        | 0.26%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 23        | 0.26%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch            | 23        | 0.26%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                    | 23        | 0.26%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                   | 22        | 0.25%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 22        | 0.25%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch              | 21        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch          | 21        | 0.24%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch            | 21        | 0.24%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch             | 21        | 0.24%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 21        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 20        | 0.23%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch          | 20        | 0.23%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 19        | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3899      | 47.65%  |
| 1366x768 (WXGA)    | 1782      | 21.78%  |
| 3840x2160 (4K)     | 406       | 4.96%   |
| 2560x1440 (QHD)    | 317       | 3.87%   |
| 1600x900 (HD+)     | 295       | 3.61%   |
| 1920x1200 (WUXGA)  | 273       | 3.34%   |
| 2560x1600          | 206       | 2.52%   |
| 1280x800 (WXGA)    | 195       | 2.38%   |
| 1440x900 (WXGA+)   | 144       | 1.76%   |
| 2880x1800          | 135       | 1.65%   |
| 2560x1080          | 68        | 0.83%   |
| 3840x2400          | 60        | 0.73%   |
| 3440x1440          | 51        | 0.62%   |
| 1680x1050 (WSXGA+) | 43        | 0.53%   |
| 2160x1440          | 35        | 0.43%   |
| 1280x1024 (SXGA)   | 24        | 0.29%   |
| 2256x1504          | 23        | 0.28%   |
| 3200x1800 (QHD+)   | 22        | 0.27%   |
| 1360x768           | 22        | 0.27%   |
| 3072x1920          | 21        | 0.26%   |
| 3200x2000          | 17        | 0.21%   |
| 3840x1080          | 15        | 0.18%   |
| 1920x540           | 15        | 0.18%   |
| 3000x2000          | 12        | 0.15%   |
| 3456x2160          | 9         | 0.11%   |
| Unknown            | 9         | 0.11%   |
| 3840x1100          | 8         | 0.1%    |
| 2304x1440          | 8         | 0.1%    |
| 1920x1280          | 8         | 0.1%    |
| 2880x1620          | 5         | 0.06%   |
| 2240x1400          | 5         | 0.06%   |
| 800x1280           | 4         | 0.05%   |
| 2560x1700          | 4         | 0.05%   |
| 2520x1680          | 4         | 0.05%   |
| 1280x720 (HD)      | 4         | 0.05%   |
| 2288x1287          | 3         | 0.04%   |
| 1680x945           | 3         | 0.04%   |
| 3840x1600          | 2         | 0.02%   |
| 3840x1200          | 2         | 0.02%   |
| 2880x1920          | 2         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 3501      | 40.27%  |
| 13      | 1286      | 14.79%  |
| 14      | 1042      | 11.99%  |
| 17      | 613       | 7.05%   |
| 27      | 316       | 3.63%   |
| 16      | 293       | 3.37%   |
| 24      | 273       | 3.14%   |
| 21      | 185       | 2.13%   |
| 23      | 180       | 2.07%   |
| 12      | 167       | 1.92%   |
| 31      | 161       | 1.85%   |
| 34      | 91        | 1.05%   |
| 11      | 90        | 1.04%   |
| 18      | 73        | 0.84%   |
| Unknown | 56        | 0.64%   |
| 19      | 41        | 0.47%   |
| 84      | 34        | 0.39%   |
| 32      | 29        | 0.33%   |
| 40      | 28        | 0.32%   |
| 20      | 24        | 0.28%   |
| 22      | 20        | 0.23%   |
| 63      | 18        | 0.21%   |
| 72      | 17        | 0.2%    |
| 48      | 17        | 0.2%    |
| 54      | 14        | 0.16%   |
| 25      | 11        | 0.13%   |
| 35      | 9         | 0.1%    |
| 28      | 9         | 0.1%    |
| 26      | 8         | 0.09%   |
| 52      | 7         | 0.08%   |
| 46      | 7         | 0.08%   |
| 29      | 7         | 0.08%   |
| 49      | 6         | 0.07%   |
| 65      | 5         | 0.06%   |
| 42      | 5         | 0.06%   |
| 39      | 5         | 0.06%   |
| 33      | 5         | 0.06%   |
| 10      | 5         | 0.06%   |
| 8       | 4         | 0.05%   |
| 74      | 3         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 5332      | 61.78%  |
| 201-300        | 922       | 10.68%  |
| 351-400        | 744       | 8.62%   |
| 501-600        | 707       | 8.19%   |
| 401-500        | 321       | 3.72%   |
| 601-700        | 217       | 2.51%   |
| 701-800        | 127       | 1.47%   |
| 1001-1500      | 83        | 0.96%   |
| 1501-2000      | 56        | 0.65%   |
| Unknown        | 56        | 0.65%   |
| 801-900        | 43        | 0.5%    |
| 901-1000       | 11        | 0.13%   |
| 101-200        | 5         | 0.06%   |
| 1-100          | 4         | 0.05%   |
| More than 2000 | 2         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 6196      | 81.36%  |
| 16/10   | 1107      | 14.54%  |
| 21/9    | 109       | 1.43%   |
| 3/2     | 95        | 1.25%   |
| Unknown | 28        | 0.37%   |
| 5/4     | 26        | 0.34%   |
| 32/9    | 18        | 0.24%   |
| 4/3     | 10        | 0.13%   |
| 3.40    | 8         | 0.11%   |
| 0.67    | 3         | 0.04%   |
| 6/5     | 2         | 0.03%   |
| 3.73    | 2         | 0.03%   |
| 0.89    | 2         | 0.03%   |
| 0.63    | 2         | 0.03%   |
| 0.62    | 2         | 0.03%   |
| 0.56    | 2         | 0.03%   |
| 3.20    | 1         | 0.01%   |
| 2.00    | 1         | 0.01%   |
| 1.96    | 1         | 0.01%   |
| 1.00    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 3500      | 40.38%  |
| 81-90          | 1880      | 21.69%  |
| 121-130        | 566       | 6.53%   |
| 201-250        | 543       | 6.26%   |
| 71-80          | 424       | 4.89%   |
| 301-350        | 322       | 3.71%   |
| 351-500        | 296       | 3.41%   |
| 111-120        | 275       | 3.17%   |
| 61-70          | 158       | 1.82%   |
| More than 1000 | 114       | 1.32%   |
| 151-200        | 100       | 1.15%   |
| 51-60          | 98        | 1.13%   |
| 251-300        | 87        | 1%      |
| 141-150        | 80        | 0.92%   |
| 501-1000       | 78        | 0.9%    |
| Unknown        | 56        | 0.65%   |
| 131-140        | 52        | 0.6%    |
| 91-100         | 25        | 0.29%   |
| 1-40           | 9         | 0.1%    |
| 41-50          | 5         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 3802      | 44.58%  |
| 101-120       | 2179      | 25.55%  |
| 51-100        | 1154      | 13.53%  |
| 161-240       | 848       | 9.94%   |
| More than 240 | 372       | 4.36%   |
| 1-50          | 117       | 1.37%   |
| Unknown       | 56        | 0.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 5954      | 77.96%  |
| 2     | 1297      | 16.98%  |
| 0     | 218       | 2.85%   |
| 3     | 155       | 2.03%   |
| 4     | 12        | 0.16%   |
| 6     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4080      | 33.77%  |
| Intel                             | 3986      | 32.99%  |
| Qualcomm Atheros                  | 1424      | 11.79%  |
| Broadcom                          | 799       | 6.61%   |
| MediaTek                          | 374       | 3.1%    |
| Broadcom Limited                  | 232       | 1.92%   |
| Shenzhen Goodix Technology        | 107       | 0.89%   |
| ASIX Electronics                  | 103       | 0.85%   |
| Marvell Technology Group          | 83        | 0.69%   |
| Nvidia                            | 75        | 0.62%   |
| TP-Link                           | 73        | 0.6%    |
| Ralink                            | 73        | 0.6%    |
| Samsung Electronics               | 59        | 0.49%   |
| Ralink Technology                 | 56        | 0.46%   |
| Dell                              | 43        | 0.36%   |
| Qualcomm                          | 41        | 0.34%   |
| Lenovo                            | 41        | 0.34%   |
| DisplayLink                       | 40        | 0.33%   |
| Xiaomi                            | 34        | 0.28%   |
| Sierra Wireless                   | 34        | 0.28%   |
| Ericsson Business Mobile Networks | 25        | 0.21%   |
| OPPO Electronics                  | 23        | 0.19%   |
| JMicron Technology                | 22        | 0.18%   |
| Google                            | 21        | 0.17%   |
| NetGear                           | 20        | 0.17%   |
| Hewlett-Packard                   | 19        | 0.16%   |
| Huawei Technologies               | 18        | 0.15%   |
| ASUSTek Computer                  | 17        | 0.14%   |
| Motorola PCS                      | 15        | 0.12%   |
| D-Link                            | 13        | 0.11%   |
| OnePlus Technology (Shenzhen)     | 12        | 0.1%    |
| Fibocom                           | 11        | 0.09%   |
| Qualcomm Atheros Communications   | 9         | 0.07%   |
| Silicon Integrated Systems [SiS]  | 8         | 0.07%   |
| Microsoft                         | 8         | 0.07%   |
| Apple                             | 8         | 0.07%   |
| Qualcomm Technologies             | 6         | 0.05%   |
| Edimax Technology                 | 6         | 0.05%   |
| Linksys                           | 5         | 0.04%   |
| Arduino SA                        | 4         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2587      | 18.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 551       | 3.87%   |
| Intel Wi-Fi 6 AX200                                                    | 441       | 3.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 335       | 2.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 312       | 2.19%   |
| Intel Wireless 8265 / 8275                                             | 294       | 2.07%   |
| Intel Wi-Fi 6 AX201                                                    | 259       | 1.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 230       | 1.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 224       | 1.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 224       | 1.57%   |
| Intel Wireless 7260                                                    | 224       | 1.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 221       | 1.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 210       | 1.48%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 205       | 1.44%   |
| Intel Wireless 7265                                                    | 202       | 1.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 199       | 1.4%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 197       | 1.38%   |
| Intel Wireless 8260                                                    | 191       | 1.34%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 190       | 1.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 173       | 1.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 158       | 1.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 132       | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 132       | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 131       | 0.92%   |
| Intel Ethernet Connection (4) I219-LM                                  | 110       | 0.77%   |
| Broadcom BCM43142 802.11b/g/n                                          | 108       | 0.76%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 106       | 0.74%   |
| Shenzhen Goodix Fingerprint Reader                                     | 105       | 0.74%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 103       | 0.72%   |
| Intel Wireless 3165                                                    | 100       | 0.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                         | 97        | 0.68%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 97        | 0.68%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 96        | 0.67%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 92        | 0.65%   |
| Intel Ethernet Connection I219-LM                                      | 90        | 0.63%   |
| ASIX AX88179 Gigabit Ethernet                                          | 90        | 0.63%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 82        | 0.58%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 80        | 0.56%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 77        | 0.54%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 77        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3770      | 49.19%  |
| Qualcomm Atheros                      | 1187      | 15.49%  |
| Realtek Semiconductor                 | 1068      | 13.94%  |
| Broadcom                              | 690       | 9%      |
| MediaTek                              | 349       | 4.55%   |
| Broadcom Limited                      | 194       | 2.53%   |
| Ralink                                | 73        | 0.95%   |
| TP-Link                               | 62        | 0.81%   |
| Ralink Technology                     | 56        | 0.73%   |
| Dell                                  | 35        | 0.46%   |
| Sierra Wireless                       | 34        | 0.44%   |
| Qualcomm                              | 34        | 0.44%   |
| NetGear                               | 17        | 0.22%   |
| ASUSTek Computer                      | 14        | 0.18%   |
| D-Link                                | 12        | 0.16%   |
| Fibocom                               | 11        | 0.14%   |
| Qualcomm Atheros Communications       | 9         | 0.12%   |
| Hewlett-Packard                       | 8         | 0.1%    |
| Microsoft                             | 7         | 0.09%   |
| Qualcomm Technologies                 | 6         | 0.08%   |
| Edimax Technology                     | 6         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.04%   |
| Linksys                               | 2         | 0.03%   |
| D-Link System                         | 2         | 0.03%   |
| AVM                                   | 2         | 0.03%   |
| ZyDAS                                 | 1         | 0.01%   |
| Wilocity                              | 1         | 0.01%   |
| Sitecom Europe                        | 1         | 0.01%   |
| Senao                                 | 1         | 0.01%   |
| Samsung Electronics                   | 1         | 0.01%   |
| Realtek                               | 1         | 0.01%   |
| Philips (or NXP)                      | 1         | 0.01%   |
| Ovislink                              | 1         | 0.01%   |
| Micro Star International              | 1         | 0.01%   |
| Chu Yuen Enterprise                   | 1         | 0.01%   |
| BUFFALO                               | 1         | 0.01%   |
| Arduino SA                            | 1         | 0.01%   |
| Accton Technology                     | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 441       | 5.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 312       | 4.05%   |
| Intel Wireless 8265 / 8275                                           | 294       | 3.81%   |
| Intel Wi-Fi 6 AX201                                                  | 259       | 3.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 224       | 2.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 224       | 2.91%   |
| Intel Wireless 7260                                                  | 224       | 2.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 221       | 2.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 210       | 2.72%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 205       | 2.66%   |
| Intel Wireless 7265                                                  | 202       | 2.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 199       | 2.58%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 197       | 2.56%   |
| Intel Wireless 8260                                                  | 191       | 2.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 173       | 2.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 158       | 2.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 132       | 1.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 132       | 1.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 131       | 1.7%    |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 130       | 1.69%   |
| Broadcom BCM43142 802.11b/g/n                                        | 108       | 1.4%    |
| Broadcom BCM4331 802.11a/b/g/n                                       | 106       | 1.38%   |
| Intel Wireless 3165                                                  | 100       | 1.3%    |
| Intel Tiger Lake PCH CNVi WiFi                                       | 97        | 1.26%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 97        | 1.26%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 96        | 1.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 80        | 1.04%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 77        | 1%      |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 77        | 1%      |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 73        | 0.95%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 73        | 0.95%   |
| Intel Wireless 3160                                                  | 73        | 0.95%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 71        | 0.92%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 70        | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 69        | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 63        | 0.82%   |
| Intel Centrino Ultimate-N 6300                                       | 61        | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 60        | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 60        | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 55        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3645      | 58.55%  |
| Intel                                  | 1248      | 20.05%  |
| Qualcomm Atheros                       | 382       | 6.14%   |
| Broadcom                               | 272       | 4.37%   |
| ASIX Electronics                       | 103       | 1.65%   |
| Marvell Technology Group               | 83        | 1.33%   |
| Nvidia                                 | 75        | 1.2%    |
| Samsung Electronics                    | 58        | 0.93%   |
| Broadcom Limited                       | 43        | 0.69%   |
| Lenovo                                 | 41        | 0.66%   |
| DisplayLink                            | 40        | 0.64%   |
| Xiaomi                                 | 34        | 0.55%   |
| MediaTek                               | 25        | 0.4%    |
| OPPO Electronics                       | 23        | 0.37%   |
| JMicron Technology                     | 22        | 0.35%   |
| Google                                 | 21        | 0.34%   |
| Motorola PCS                           | 15        | 0.24%   |
| Huawei Technologies                    | 13        | 0.21%   |
| TP-Link                                | 11        | 0.18%   |
| OnePlus Technology (Shenzhen)          | 11        | 0.18%   |
| Silicon Integrated Systems [SiS]       | 8         | 0.13%   |
| Qualcomm                               | 7         | 0.11%   |
| Apple                                  | 7         | 0.11%   |
| Hewlett-Packard                        | 4         | 0.06%   |
| T & A Mobile Phones                    | 3         | 0.05%   |
| NetGear                                | 3         | 0.05%   |
| Linksys                                | 3         | 0.05%   |
| ICS Advent                             | 3         | 0.05%   |
| ASUSTek Computer                       | 3         | 0.05%   |
| Suzhou Motorcomm Electronic Technology | 2         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.03%   |
| LSI                                    | 2         | 0.03%   |
| LG Electronics                         | 2         | 0.03%   |
| Aquantia                               | 2         | 0.03%   |
| Research In Motion                     | 1         | 0.02%   |
| Motorcomm Microelectronics.            | 1         | 0.02%   |
| Microsoft                              | 1         | 0.02%   |
| Foxconn / Hon Hai                      | 1         | 0.02%   |
| D-Link                                 | 1         | 0.02%   |
| Cypress Semiconductor                  | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2587      | 40.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 551       | 8.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 335       | 5.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 230       | 3.62%   |
| Intel Ethernet Connection (4) I219-LM                                  | 110       | 1.73%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 103       | 1.62%   |
| Intel Ethernet Connection I219-LM                                      | 90        | 1.42%   |
| ASIX AX88179 Gigabit Ethernet                                          | 90        | 1.42%   |
| Realtek RTL8125 2.5GbE Controller                                      | 76        | 1.2%    |
| Intel Ethernet Connection I218-LM                                      | 75        | 1.18%   |
| Intel Ethernet Connection I217-LM                                      | 65        | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 64        | 1.01%   |
| Realtek Killer E2600 GbE Controller                                    | 62        | 0.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 60        | 0.95%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 56        | 0.88%   |
| Intel Ethernet Connection (3) I218-LM                                  | 56        | 0.88%   |
| Nvidia MCP79 Ethernet                                                  | 55        | 0.87%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 54        | 0.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 47        | 0.74%   |
| Intel Ethernet Connection (4) I219-V                                   | 45        | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                                  | 41        | 0.65%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 39        | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 38        | 0.6%    |
| Intel 82577LM Gigabit Network Connection                               | 37        | 0.58%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 36        | 0.57%   |
| Intel Ethernet Connection I219-V                                       | 33        | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 32        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                                  | 31        | 0.49%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 31        | 0.49%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 31        | 0.49%   |
| Intel Ethernet Connection (6) I219-V                                   | 29        | 0.46%   |
| Intel Ethernet Connection (13) I219-V                                  | 29        | 0.46%   |
| Intel Ethernet Connection (6) I219-LM                                  | 27        | 0.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 26        | 0.41%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 26        | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 26        | 0.41%   |
| Intel 82567LM Gigabit Network Connection                               | 26        | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 25        | 0.39%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 24        | 0.38%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 23        | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 7262      | 54.61%  |
| Ethernet | 5859      | 44.06%  |
| Modem    | 163       | 1.23%   |
| Unknown  | 13        | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 6181      | 77.98%  |
| Ethernet | 1744      | 22%     |
| Modem    | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 5268      | 70.56%  |
| 1     | 2095      | 28.06%  |
| 0     | 52        | 0.7%    |
| 3     | 51        | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5617      | 73.92%  |
| Yes  | 1982      | 26.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3315      | 51.06%  |
| Realtek Semiconductor           | 597       | 9.2%    |
| Qualcomm Atheros Communications | 551       | 8.49%   |
| Apple                           | 418       | 6.44%   |
| IMC Networks                    | 392       | 6.04%   |
| Lite-On Technology              | 265       | 4.08%   |
| Foxconn / Hon Hai               | 261       | 4.02%   |
| Broadcom                        | 248       | 3.82%   |
| Dell                            | 97        | 1.49%   |
| Cambridge Silicon Radio         | 51        | 0.79%   |
| Realtek                         | 46        | 0.71%   |
| Hewlett-Packard                 | 42        | 0.65%   |
| Toshiba                         | 40        | 0.62%   |
| Ralink                          | 40        | 0.62%   |
| MediaTek                        | 31        | 0.48%   |
| ASUSTek Computer                | 20        | 0.31%   |
| USI                             | 13        | 0.2%    |
| Foxconn International           | 13        | 0.2%    |
| Ralink Technology               | 9         | 0.14%   |
| Alps Electric                   | 9         | 0.14%   |
| Smart Modular Technologies      | 5         | 0.08%   |
| Qcom                            | 4         | 0.06%   |
| Opticis                         | 4         | 0.06%   |
| Askey Computer                  | 4         | 0.06%   |
| TP-Link                         | 3         | 0.05%   |
| Taiyo Yuden                     | 3         | 0.05%   |
| Actions                         | 3         | 0.05%   |
| Fujitsu                         | 2         | 0.03%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Quectel Wireless Solutions      | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Integrated System Solution      | 1         | 0.02%   |
| Dynex                           | 1         | 0.02%   |
| Creative Technology             | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1049      | 16.15%  |
| Intel AX201 Bluetooth                               | 701       | 10.79%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 507       | 7.8%    |
| Intel AX200 Bluetooth                               | 433       | 6.66%   |
| Realtek Bluetooth Radio                             | 393       | 6.05%   |
| Qualcomm Atheros  Bluetooth Device                  | 304       | 4.68%   |
| Intel Bluetooth Device                              | 278       | 4.28%   |
| Apple Bluetooth Host Controller                     | 244       | 3.76%   |
| IMC Networks Wireless_Device                        | 165       | 2.54%   |
| Realtek  Bluetooth 4.2 Adapter                      | 139       | 2.14%   |
| Apple Bluetooth USB Host Controller                 | 133       | 2.05%   |
| IMC Networks Bluetooth Radio                        | 104       | 1.6%    |
| Intel AX210 Bluetooth                               | 93        | 1.43%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 88        | 1.35%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 86        | 1.32%   |
| Foxconn / Hon Hai Bluetooth Device                  | 76        | 1.17%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 68        | 1.05%   |
| Foxconn / Hon Hai Wireless_Device                   | 68        | 1.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 64        | 0.99%   |
| IMC Networks Bluetooth Device                       | 61        | 0.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 57        | 0.88%   |
| Lite-On Bluetooth Device                            | 57        | 0.88%   |
| Intel Wireless-AC 3168 Bluetooth                    | 54        | 0.83%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 52        | 0.8%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 51        | 0.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 51        | 0.78%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 48        | 0.74%   |
| Realtek Bluetooth Radio                             | 46        | 0.71%   |
| Broadcom BCM2045B (BDC-2.1)                         | 46        | 0.71%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 42        | 0.65%   |
| Ralink RT3290 Bluetooth                             | 40        | 0.62%   |
| Lite-On Wireless_Device                             | 38        | 0.58%   |
| Dell DW375 Bluetooth Module                         | 32        | 0.49%   |
| MediaTek Wireless_Device                            | 31        | 0.48%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 31        | 0.48%   |
| Dell BCM20702A0 Bluetooth Module                    | 28        | 0.43%   |
| Lite-On Atheros AR3012 Bluetooth                    | 27        | 0.42%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 26        | 0.4%    |
| HP Broadcom 2070 Bluetooth Combo                    | 26        | 0.4%    |
| Apple Bluetooth HCI                                 | 22        | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5816      | 58.42%  |
| Nvidia                           | 1818      | 18.26%  |
| AMD                              | 1639      | 16.46%  |
| C-Media Electronics              | 71        | 0.71%   |
| Logitech                         | 69        | 0.69%   |
| Realtek Semiconductor            | 54        | 0.54%   |
| Lenovo                           | 44        | 0.44%   |
| GN Netcom                        | 33        | 0.33%   |
| JMTek                            | 30        | 0.3%    |
| Sony                             | 26        | 0.26%   |
| Apple                            | 25        | 0.25%   |
| Kingston Technology              | 22        | 0.22%   |
| Texas Instruments                | 19        | 0.19%   |
| Hewlett-Packard                  | 19        | 0.19%   |
| Generalplus Technology           | 19        | 0.19%   |
| Plantronics                      | 18        | 0.18%   |
| SteelSeries ApS                  | 17        | 0.17%   |
| Razer USA                        | 15        | 0.15%   |
| Corsair                          | 15        | 0.15%   |
| Focusrite-Novation               | 10        | 0.1%    |
| Silicon Integrated Systems [SiS] | 8         | 0.08%   |
| FiiO Electronics Technology      | 7         | 0.07%   |
| Creative Technology              | 7         | 0.07%   |
| ASUSTek Computer                 | 7         | 0.07%   |
| Walmart                          | 6         | 0.06%   |
| DSEA A/S                         | 6         | 0.06%   |
| Blue Microphones                 | 6         | 0.06%   |
| Turtle Beach                     | 4         | 0.04%   |
| Samson Technologies              | 4         | 0.04%   |
| BEHRINGER International          | 4         | 0.04%   |
| Yamaha                           | 3         | 0.03%   |
| TerraTec Electronic              | 3         | 0.03%   |
| Tenx Technology                  | 3         | 0.03%   |
| Sennheiser Communications        | 3         | 0.03%   |
| Nordic Semiconductor ASA         | 3         | 0.03%   |
| No brand                         | 3         | 0.03%   |
| Microsoft                        | 3         | 0.03%   |
| GYROCOM C&C                      | 3         | 0.03%   |
| FIFINE Microphones               | 3         | 0.03%   |
| Dell                             | 3         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 1165      | 9.64%   |
| Intel Sunrise Point-LP HD Audio                                            | 807       | 6.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 531       | 4.39%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 499       | 4.13%   |
| Intel Cannon Lake PCH cAVS                                                 | 464       | 3.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 416       | 3.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 336       | 2.78%   |
| Intel 8 Series HD Audio Controller                                         | 333       | 2.75%   |
| Intel Haswell-ULT HD Audio Controller                                      | 331       | 2.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 297       | 2.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 290       | 2.4%    |
| Intel Broadwell-U Audio Controller                                         | 281       | 2.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 271       | 2.24%   |
| Intel Comet Lake PCH cAVS                                                  | 244       | 2.02%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 238       | 1.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 227       | 1.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 219       | 1.81%   |
| Intel Comet Lake PCH-LP cAVS                                               | 214       | 1.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 197       | 1.63%   |
| AMD Radeon High Definition Audio Controller                                | 197       | 1.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 194       | 1.6%    |
| Intel CM238 HD Audio Controller                                            | 193       | 1.6%    |
| Nvidia TU106 High Definition Audio Controller                              | 172       | 1.42%   |
| AMD FCH Azalia Controller                                                  | 166       | 1.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 140       | 1.16%   |
| Nvidia GA106 High Definition Audio Controller                              | 135       | 1.12%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 135       | 1.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 134       | 1.11%   |
| Nvidia GP107GL High Definition Audio Controller                            | 129       | 1.07%   |
| Nvidia GA104 High Definition Audio Controller                              | 128       | 1.06%   |
| Nvidia GA107 High Definition Audio Controller                              | 124       | 1.03%   |
| Nvidia AD107 High Definition Audio Controller                              | 113       | 0.93%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 103       | 0.85%   |
| AMD Kabini HDMI/DP Audio                                                   | 102       | 0.84%   |
| Nvidia GP106 High Definition Audio Controller                              | 93        | 0.77%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 89        | 0.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 88        | 0.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 84        | 0.69%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 76        | 0.63%   |
| Nvidia TU116 High Definition Audio Controller                              | 75        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 737       | 28.32%  |
| SK hynix            | 581       | 22.33%  |
| Micron Technology   | 381       | 14.64%  |
| Kingston            | 201       | 7.72%   |
| Crucial             | 159       | 6.11%   |
| Unknown             | 76        | 2.92%   |
| A-DATA Technology   | 60        | 2.31%   |
| Corsair             | 50        | 1.92%   |
| Ramaxel Technology  | 46        | 1.77%   |
| Unknown             | 39        | 1.5%    |
| Smart               | 36        | 1.38%   |
| Elpida              | 30        | 1.15%   |
| Neo Forza           | 27        | 1.04%   |
| Goldkey             | 25        | 0.96%   |
| G.Skill             | 21        | 0.81%   |
| Team                | 15        | 0.58%   |
| Unknown (ABCD)      | 14        | 0.54%   |
| Smart Brazil        | 12        | 0.46%   |
| Nanya Technology    | 8         | 0.31%   |
| Teikon              | 7         | 0.27%   |
| Timetec             | 6         | 0.23%   |
| PNY                 | 5         | 0.19%   |
| GSkill              | 5         | 0.19%   |
| Apacer              | 5         | 0.19%   |
| Transcend           | 3         | 0.12%   |
| Patriot             | 3         | 0.12%   |
| High Bridge         | 3         | 0.12%   |
| GOODRAM             | 3         | 0.12%   |
| ChangXin Memory     | 3         | 0.12%   |
| Avant               | 3         | 0.12%   |
| Silicon Power       | 2         | 0.08%   |
| Gold Key            | 2         | 0.08%   |
| CSX                 | 2         | 0.08%   |
| ASint Technology    | 2         | 0.08%   |
| Wilk                | 1         | 0.04%   |
| Unknown (8A02)      | 1         | 0.04%   |
| Unknown (898F)      | 1         | 0.04%   |
| Unknown (0x0E2A)    | 1         | 0.04%   |
| Unknown (0x0CAB)    | 1         | 0.04%   |
| Unknown (0x0C26)    | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 54        | 1.98%   |
| Unknown                                                          | 39        | 1.43%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 38        | 1.39%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 37        | 1.35%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 32        | 1.17%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 30        | 1.1%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 28        | 1.03%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 24        | 0.88%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 22        | 0.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 21        | 0.77%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 19        | 0.7%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 19        | 0.7%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 19        | 0.7%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 19        | 0.7%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 19        | 0.7%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 18        | 0.66%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 17        | 0.62%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 17        | 0.62%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 0.62%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 17        | 0.62%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 17        | 0.62%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 16        | 0.59%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 15        | 0.55%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 0.55%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 15        | 0.55%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 15        | 0.55%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 15        | 0.55%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 14        | 0.51%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.51%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 14        | 0.51%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 14        | 0.51%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 14        | 0.51%   |
| Neo Forza RAM NMSO432F82-3200E 32GB SODIMM DDR4 3200MT/s         | 14        | 0.51%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.48%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 13        | 0.48%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 13        | 0.48%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 12        | 0.44%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 12        | 0.44%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 11        | 0.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1349      | 61.4%   |
| DDR3    | 365       | 16.61%  |
| DDR5    | 159       | 7.24%   |
| LPDDR5  | 111       | 5.05%   |
| LPDDR4  | 106       | 4.82%   |
| LPDDR3  | 84        | 3.82%   |
| DDR2    | 12        | 0.55%   |
| SDRAM   | 7         | 0.32%   |
| Unknown | 4         | 0.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1886      | 84.42%  |
| Row Of Chips | 319       | 14.28%  |
| Chip         | 16        | 0.72%   |
| Unknown      | 9         | 0.4%    |
| DIMM         | 4         | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1058      | 43.96%  |
| 16384 | 537       | 22.31%  |
| 4096  | 523       | 21.73%  |
| 32768 | 175       | 7.27%   |
| 2048  | 95        | 3.95%   |
| 1024  | 13        | 0.54%   |
| 3072  | 2         | 0.08%   |
| 49152 | 1         | 0.04%   |
| 24576 | 1         | 0.04%   |
| 12288 | 1         | 0.04%   |
| 6144  | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 668       | 27.97%  |
| 2667    | 553       | 23.16%  |
| 1600    | 285       | 11.93%  |
| 2400    | 183       | 7.66%   |
| 2133    | 116       | 4.86%   |
| 4800    | 93        | 3.89%   |
| 5600    | 68        | 2.85%   |
| 6400    | 67        | 2.81%   |
| 4267    | 49        | 2.05%   |
| 8400    | 43        | 1.8%    |
| 1334    | 33        | 1.38%   |
| 3266    | 32        | 1.34%   |
| 1867    | 31        | 1.3%    |
| 1333    | 28        | 1.17%   |
| 7500    | 25        | 1.05%   |
| 4266    | 19        | 0.8%    |
| 1067    | 15        | 0.63%   |
| 800     | 10        | 0.42%   |
| 8533    | 8         | 0.34%   |
| 3733    | 8         | 0.34%   |
| 2933    | 6         | 0.25%   |
| 1866    | 5         | 0.21%   |
| 667     | 5         | 0.21%   |
| Unknown | 5         | 0.21%   |
| 8600    | 4         | 0.17%   |
| 3000    | 4         | 0.17%   |
| 2048    | 4         | 0.17%   |
| 7467    | 3         | 0.13%   |
| 5200    | 3         | 0.13%   |
| 4199    | 3         | 0.13%   |
| 5500    | 2         | 0.08%   |
| 3333    | 2         | 0.08%   |
| 1066    | 2         | 0.08%   |
| 8000    | 1         | 0.04%   |
| 3466    | 1         | 0.04%   |
| 3400    | 1         | 0.04%   |
| 1200    | 1         | 0.04%   |
| 975     | 1         | 0.04%   |
| 666     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 11        | 30.56%  |
| Canon               | 7         | 19.44%  |
| Seiko Epson         | 6         | 16.67%  |
| Brother Industries  | 5         | 13.89%  |
| Samsung Electronics | 3         | 8.33%   |
| Xerox               | 1         | 2.78%   |
| MIIIW               | 1         | 2.78%   |
| ICS Advent          | 1         | 2.78%   |
| Dymo-CoStar         | 1         | 2.78%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Samsung M2020 Series             | 2         | 5.56%   |
| Canon PIXMA MX920 Series         | 2         | 5.56%   |
| Xerox B215                       | 1         | 2.78%   |
| Seiko Epson L380 Series          | 1         | 2.78%   |
| Seiko Epson L3110 Series         | 1         | 2.78%   |
| Seiko Epson ET-3750 Series       | 1         | 2.78%   |
| Seiko Epson ET-2700 Series       | 1         | 2.78%   |
| Seiko Epson EPSON WF-3520 Series | 1         | 2.78%   |
| Seiko Epson EPSON L132 Series    | 1         | 2.78%   |
| Samsung SCX-4600 Series          | 1         | 2.78%   |
| MIIIW MW Keyboard Air Mini       | 1         | 2.78%   |
| ICS Advent Parallel Adapter      | 1         | 2.78%   |
| HP OfficeJet 3830 series         | 1         | 2.78%   |
| HP Ink Tank Wireless 410 series  | 1         | 2.78%   |
| HP ENVY Photo 7800 series        | 1         | 2.78%   |
| HP ENVY 6000 series              | 1         | 2.78%   |
| HP ENVY 4520 series              | 1         | 2.78%   |
| HP DeskJet Plus 4100 series      | 1         | 2.78%   |
| HP Deskjet 3050 J610 series      | 1         | 2.78%   |
| HP Deskjet 2540 series           | 1         | 2.78%   |
| HP DeskJet 2130 series           | 1         | 2.78%   |
| HP Deskjet 2050 J510             | 1         | 2.78%   |
| HP Color LaserJet CP2025dn       | 1         | 2.78%   |
| Dymo-CoStar LabelWriter 450      | 1         | 2.78%   |
| Canon TR4700 series              | 1         | 2.78%   |
| Canon LiDE 300                   | 1         | 2.78%   |
| Canon GX7000 series              | 1         | 2.78%   |
| Canon G4010 series               | 1         | 2.78%   |
| Canon E400 series                | 1         | 2.78%   |
| Brother HL-L2370DW series        | 1         | 2.78%   |
| Brother HL-L2320D series         | 1         | 2.78%   |
| Brother HL-3170CDW series        | 1         | 2.78%   |
| Brother HL-2270DW Laser Printer  | 1         | 2.78%   |
| Brother DCP-T500W                | 1         | 2.78%   |

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
| Chicony Electronics                    | 1519      | 22.8%   |
| IMC Networks                           | 716       | 10.75%  |
| Bison Electronics                      | 649       | 9.74%   |
| Microdia                               | 607       | 9.11%   |
| Realtek Semiconductor                  | 538       | 8.08%   |
| Quanta                                 | 381       | 5.72%   |
| Sunplus Innovation Technology          | 357       | 5.36%   |
| Apple                                  | 296       | 4.44%   |
| Cheng Uei Precision Industry (Foxlink) | 210       | 3.15%   |
| Syntek                                 | 176       | 2.64%   |
| Luxvisions Innotech Limited            | 173       | 2.6%    |
| Suyin                                  | 166       | 2.49%   |
| Lite-On Technology                     | 143       | 2.15%   |
| Logitech                               | 88        | 1.32%   |
| Silicon Motion                         | 80        | 1.2%    |
| Sonix Technology                       | 74        | 1.11%   |
| Ricoh                                  | 47        | 0.71%   |
| Alcor Micro                            | 47        | 0.71%   |
| Samsung Electronics                    | 39        | 0.59%   |
| Acer                                   | 35        | 0.53%   |
| SunplusIT                              | 30        | 0.45%   |
| ShineTech                              | 30        | 0.45%   |
| Primax Electronics                     | 15        | 0.23%   |
| ALi                                    | 15        | 0.23%   |
| Microsoft                              | 14        | 0.21%   |
| Importek                               | 13        | 0.2%    |
| Z-Star Microelectronics                | 12        | 0.18%   |
| OmniVision Technologies                | 11        | 0.17%   |
| Lenovo                                 | 11        | 0.17%   |
| Intel                                  | 10        | 0.15%   |
| DigiTech                               | 10        | 0.15%   |
| kingcome                               | 9         | 0.14%   |
| Generalplus Technology                 | 8         | 0.12%   |
| icSpring                               | 7         | 0.11%   |
| Tobii Technology AB                    | 5         | 0.08%   |
| Razer USA                              | 5         | 0.08%   |
| AVerMedia Technologies                 | 5         | 0.08%   |
| Unknown                                | 4         | 0.06%   |
| Sunplus Technology                     | 4         | 0.06%   |
| Shine-optics                           | 4         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 331       | 4.94%   |
| Microdia Integrated_Webcam_HD                       | 330       | 4.93%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 238       | 3.55%   |
| IMC Networks Integrated Camera                      | 201       | 3%      |
| Realtek Integrated_Webcam_HD                        | 200       | 2.99%   |
| Chicony HD WebCam                                   | 171       | 2.55%   |
| Bison BisonCam,NB Pro                               | 154       | 2.3%    |
| Bison Integrated Camera                             | 126       | 1.88%   |
| Syntek Integrated Camera                            | 118       | 1.76%   |
| Apple FaceTime HD Camera                            | 104       | 1.55%   |
| Sunplus Integrated_Webcam_HD                        | 96        | 1.43%   |
| Apple Built-in iSight                               | 85        | 1.27%   |
| Quanta HD User Facing                               | 83        | 1.24%   |
| Bison HD Webcam                                     | 81        | 1.21%   |
| Chicony USB2.0 Camera                               | 80        | 1.19%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 71        | 1.06%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 65        | 0.97%   |
| Chicony Chicony USB2.0 Camera                       | 63        | 0.94%   |
| Lite-On Integrated Camera                           | 59        | 0.88%   |
| Chicony HP HD Camera                                | 55        | 0.82%   |
| Bison SunplusIT Integrated Camera                   | 53        | 0.79%   |
| Quanta HD Webcam                                    | 52        | 0.78%   |
| Chicony HD User Facing                              | 52        | 0.78%   |
| Sonix USB2.0 HD UVC WebCam                          | 48        | 0.72%   |
| Luxvisions Innotech Limited Integrated Camera       | 46        | 0.69%   |
| Microdia Integrated Webcam                          | 45        | 0.67%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 45        | 0.67%   |
| Chicony USB 2.0 Camera                              | 44        | 0.66%   |
| Chicony HP Truevision HD camera                     | 44        | 0.66%   |
| Bison BisonCam, NB Pro                              | 44        | 0.66%   |
| Microdia Laptop_Integrated_Webcam_HD                | 43        | 0.64%   |
| Chicony USB2.0 HD UVC WebCam                        | 43        | 0.64%   |
| Chicony Integrated Camera (1280x720@30)             | 43        | 0.64%   |
| Chicony HP Wide Vision HD Camera                    | 42        | 0.63%   |
| Quanta HP TrueVision HD Camera                      | 41        | 0.61%   |
| Realtek USB Camera                                  | 40        | 0.6%    |
| Sunplus ASUS Webcam                                 | 39        | 0.58%   |
| Sunplus HD WebCam                                   | 38        | 0.57%   |
| Chicony TOSHIBA Web Camera - HD                     | 38        | 0.57%   |
| Samsung Galaxy series, misc. (MTP mode)             | 36        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 421       | 33.82%  |
| Validity Sensors                   | 367       | 29.48%  |
| Shenzhen Goodix Technology         | 206       | 16.55%  |
| Elan Microelectronics              | 71        | 5.7%    |
| Upek                               | 62        | 4.98%   |
| LighTuning Technology              | 51        | 4.1%    |
| AuthenTec                          | 36        | 2.89%   |
| Realtek USB2.0 Finger Print Bridge | 10        | 0.8%    |
| STMicroelectronics                 | 9         | 0.72%   |
| HOLTEK                             | 5         | 0.4%    |
| Focal-systems.Corp                 | 5         | 0.4%    |
| Samsung Electronics                | 1         | 0.08%   |
| DigitalPersona                     | 1         | 0.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 138       | 11.08%  |
| Shenzhen Goodix  Fingerprint Device                                        | 114       | 9.16%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 83        | 6.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 77        | 6.18%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 56        | 4.5%    |
| Shenzhen Goodix FingerPrint                                                | 54        | 4.34%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 51        | 4.1%    |
| Elan ELAN:Fingerprint                                                      | 48        | 3.86%   |
| Shenzhen Goodix Fingerprint Reader                                         | 38        | 3.05%   |
| Synaptics TouchPad                                                         | 32        | 2.57%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 30        | 2.41%   |
| Validity Sensors Synaptics WBDI                                            | 27        | 2.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 27        | 2.17%   |
| Validity Sensors VFS491                                                    | 26        | 2.09%   |
| Validity Sensors Fingerprint scanner                                       | 26        | 2.09%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 25        | 2.01%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 24        | 1.93%   |
| Synaptics WBDI Device                                                      | 24        | 1.93%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 23        | 1.85%   |
| Elan ELAN:ARM-M4                                                           | 23        | 1.85%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 22        | 1.77%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 21        | 1.69%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 20        | 1.61%   |
| Synaptics Fingerprint reader [HP G6]                                       | 20        | 1.61%   |
| Unknown                                                                    | 17        | 1.37%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 16        | 1.29%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 1.12%   |
| Synaptics  WBDI                                                            | 14        | 1.12%   |
| Synaptics UWP WBDI Device                                                  | 12        | 0.96%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 12        | 0.96%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 12        | 0.96%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 11        | 0.88%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 10        | 0.8%    |
| Synaptics Prometheus Fingerprint Reader                                    | 9         | 0.72%   |
| STMicroelectronics Fingerprint Reader                                      | 9         | 0.72%   |
| AuthenTec Fingerprint Sensor                                               | 9         | 0.72%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 0.72%   |
| AuthenTec AES2810                                                          | 8         | 0.64%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 0.56%   |
| Upek TCS5B Fingerprint sensor                                              | 6         | 0.48%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 237       | 50.21%  |
| Alcor Micro               | 132       | 27.97%  |
| Upek                      | 35        | 7.42%   |
| O2 Micro                  | 34        | 7.2%    |
| Lenovo                    | 22        | 4.66%   |
| SCM Microsystems          | 3         | 0.64%   |
| Gemalto (was Gemplus)     | 2         | 0.42%   |
| Aladdin Knowledge Systems | 2         | 0.42%   |
| Yubico.com                | 1         | 0.21%   |
| OmniKey                   | 1         | 0.21%   |
| Giesecke & Devrient       | 1         | 0.21%   |
| Clay Logic                | 1         | 0.21%   |
| Advanced Card Systems     | 1         | 0.21%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 132       | 27.97%  |
| Broadcom BCM5880 Secure Applications Processor                               | 64        | 13.56%  |
| Broadcom 5880                                                                | 62        | 13.14%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 50        | 10.59%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 35        | 7.42%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 30        | 6.36%   |
| Broadcom 58200                                                               | 30        | 6.36%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 28        | 5.93%   |
| Lenovo Integrated Smart Card Reader                                          | 22        | 4.66%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 0.85%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 3         | 0.64%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 0.42%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.42%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.21%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.21%   |
| OmniKey CardMan 4321                                                         | 1         | 0.21%   |
| Giesecke & Devrient Chipcard Reader                                          | 1         | 0.21%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.21%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.21%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.21%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.21%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 4627      | 60.79%  |
| 1     | 2405      | 31.59%  |
| 2     | 503       | 6.61%   |
| 3     | 66        | 0.87%   |
| 4     | 7         | 0.09%   |
| 5     | 3         | 0.04%   |
| 6     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1218      | 34.35%  |
| Multimedia controller    | 517       | 14.58%  |
| Graphics card            | 488       | 13.76%  |
| Chipcard                 | 456       | 12.86%  |
| Net/wireless             | 388       | 10.94%  |
| Camera                   | 133       | 3.75%   |
| Bluetooth                | 107       | 3.02%   |
| Storage                  | 51        | 1.44%   |
| Net/ethernet             | 44        | 1.24%   |
| Sound                    | 41        | 1.16%   |
| Communication controller | 28        | 0.79%   |
| Card reader              | 28        | 0.79%   |
| Network                  | 17        | 0.48%   |
| Modem                    | 15        | 0.42%   |
| Storage/ide              | 5         | 0.14%   |
| Storage/nvme             | 3         | 0.08%   |
| Flash memory             | 2         | 0.06%   |
| Firewire controller      | 2         | 0.06%   |
| Unclassified device      | 1         | 0.03%   |
| Unassigned class         | 1         | 0.03%   |
| Dvb card                 | 1         | 0.03%   |

